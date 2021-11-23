# **Cockpit ATC**

Cockpit ATC is the business name given to the mechanism allowing SGDBF
Salespersons (“ATC”) to login under regular users accounts. It involves
:

-   **Impulse Admin** : interface on client side allowing to manage data
     (Products, Users…)

-   Drupal site

## **Usage context**


**!!** A setting allows to switch between the 2 functional behaviors
described below.

### Behavior 1 

A Salesperson (“ATC”) goes to see his Client (= User who has an account
on the website). In order to make a demo / show User how site works, he
must be able to log in as the User. It will imply some specific
restrictions, because even if Salesperson can log in as User, he will
not be able to :

-   Add to Cart (PLP, PDP, Variants popin, Quick addtocart entry, Orders
     & Documents Details etc.) =&gt; so all "Add to cart" buttons must
     have "disabled state"

-   Create, modify, remove wishlists (and adding articles to them)

-   Proceed to Checkout from the Cart Page

-   Edit Personal Info

-   Edit Users' addresses

-   Post Claims

-   Change User password

Note that ATC is able to login as a User without knowing User’s
password.

### Behavior 2 

Comparing to behavior 1, Cockpit ATC User will not have ANY restrictions
on the website, except from proceeding to an actual order.\
This means that such User can’t click on the Pay button on Checkout
(payment step). This logic must apply for both regular Vue Checkout, and
Quote to Order Checkout variant.

## **Technical solution**


From Impulse Admin, ATC people can see the list of all Users registered
on the website. For each User, a call to action “Login” allows to
trigger the process. Onclick on “Login” button, ATC is redirected to the
website, on a dedicated URL : ../cockpit. Note that this URL is a
technical one, it does not correspond to an actual page.

../cockpit URL is available for Impulse Admin to POST the following body
:

```
{
   "access_token": "eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJhY2NvdW50SWQiOiJWSV9YWFhYIiwidXNlcl9uYW1lIjoiVklfWFhYWCIsIndlYlNpdGVzIjpbImRlZmF1bHQiXSwic2NvcGUiOlsiSW1wdWxzZSJdLCJleHAiOjE1MzM2NjEwMjMsImF1dGhvcml0aWVzIjpbIlJPTEVfUEVSTV9SRUdJU1RFUmtsc2RmbGtzZGZsa21qc2RmamtsbXNkZm1rbGpmZHNtbGtqIl0sImp0aSI6IjRiZjViOGMzLWVhMjQtNDJhZC1iYTMxLWI0NzA5ZDEwNDEzNCIsImNsaWVudF9pZCI6ImRydXBhbCJ9.vcETk7wcMBvBdtbkYxSWI3RGr-DkRuFCKwxZv306CYG2BTX9eZb71MvLeuhfyznWe2wz7fw8i0PUFFdCZPDkYMH_GdCG9mq64UBTox4oLoNlhcffQBHZ01ShNB_MVjzPdilZCG0OtYVWK6HVKtQ0jgSkMeFuhSMSZj9OU0-HhE9zLY9drcxIxRx9On2c1L9ef58NyGMNeK5QrynD07ptRrC7YUHSROjceXpqS6zxLTbDrVfhErtWI2osKelM-p8H1YLtfVEa23mGObLkX8tfp5naLenKBAGC58cCQhXSJCIzE1J7LC8ykIALukcU-g8HUMXVtVbu4g0KX3_ZuI1V_w",
   "token_type": "bearer",
   "expires_in": 1799,
   "scope": "Impulse",
   "id_token": "eyJhbGciOiJSUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiJWSV9YWFhYQGRlZmF1bHQiLCJhY2NvdW50SWQiOiJWSV9YWFhYIiwicm9sZXMiOlsiUEVSTV9SRUdJU1RFUmtsc2RmbGtzZGZsa21qc2RmamtsbXNkZm1rbGpmZHNtbGtqIl0sImltcGVyc29uYXRvciI6dHJ1ZSwiU0dJRCI6Ilk4Njc0ODE5Iiwic2l0ZXMiOlsiZGVmYXVsdCJdfQ.qj2VrJDCk6NZ8gTCyjCZpnkP_E460FJ1i1Yxan8BYOfTQXiaTJZXX3TfWvEVU3bPMcmcu8f8uWQ-tAkPqAdbMJTQM_cBkheHUXDBUUbuZ8Vaamws7GUfOdm7I5LLjqqN-kZzAxfQNqIULOlMFShYWTr4cMnaZyb7qeHMrf-PyiX7j5uk8qf4Vr7sI3Xwo2CekuLLIBH42DTg09GjecpvwfH1uRfP-4U3EVGxxsHGdGfMT4Fl6UX__MGQTPBT0MCQzfaR9DAL-_nhNVXepCHmyGjS5mLCEdo5DzjYM_hOODNqe_t7hCtQPZKRH16GexWSgxqbbl1cB91JaQQsWsb33g",
   "jti": "4bf5b8c3-ea24-42ad-ba31-b4709d104134"
}
```

Decrypted id_token:
```
{
  "sub": "VI_XXXX@default",
  "accountId": "VI_XXXX",
  "roles": [
    "PERM_REGISTER"
  ],
  "impersonator": true,
  "SGID": "Y8674819",
  "sites": [
    "cedeo"
  ]
}
```

Drupal identifies “COCKPIT” role based on ‘impersonator’ value (boolean,
IF true THEN role = COCKPIT) included in the id\_token. The token/role
mapping will be stored during the entire session.

ATC is then redirected on My Account Homepage.

Drupal calls GET /accounts/{id}, authenticating with the provided
access\_token and using the 'accountId' as parameter.

All further calls will be done using the same token. There is no
refresh\_token for now, thus no related management on Drupal side. The
token validity period will be increased on services side for User
experience concerns.

As soon as token gets expired, ATC is logged out, and redirected to the
Login page. A specific warning message must be displayed on login page :

  -----------------------------------------------------------------------------------------------------------------------------------------------------------------
  Votre session a expiré. Rendez-vous sur l’interface d’Admin pour vous connecter à nouveau si vous souhaitez poursuivre votre navigation en tant qu’Utilisateur.
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------

Text is translatable from Translate Interface.\
Note that this warning message will be displayed ONLY if session gets
expired (it won’t appear if ATC logs out manually, or clears his browser
cache).

## **Restrictions**


COCKPIT role restricts next actions on the website :

-   Add to cart from all places

-   Create, modify, remove wishlists (and Add products to wishlist)

-   Process to Checkout

-   Edit personal info

-   Edit User’s addresses

-   Post claims

-   Update password

-   In EMC &gt; My orders &gt; Block Demat (Choisissez la
     dématérialisation) &gt; ATC shall not see this block


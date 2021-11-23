# **SFIC auto-login**


E-Sfic is one of the Brand websites. On this particular website, a
service called “SFIC et vous” is available for some Users.

Such Users are identified as following :

-   From Account DTO, a **services** object contains the following :

```
"services": [
    {
      "code": "ESFIC",
      "isSubscribed": true,
      "creationDate": "2019-01-01T01:00:00.000+0100",
      "updatedDate": "2019-01-01T01:00:00.000+0100",
      "agencyId": null
    }
  ],
```

If services.isSubscribed = true for code:ESFIC, then User is eligible to
the SFIC et vous service, else he is not.

Functionally, if User is registered to SFIC et vous, and accesses path
/sfic-redirect, then :

-   Service **GET /api/v1/accounts/{id}/sfic-et-vous-redirect** is
     triggered, and returns an auto-logging link. This auto-login link
     opens in a new tab by default.

If User is not registered to SFIC et vous, and accesses path
/sfic-redirect, then :

-   User is redirected to a link configured in back-office

From back-office, it is possible to set a redirect link corresponding to
/sfic-redirect.

Note that /sfic-redirect link is intended to be used in site header, but
can also be used elsewhere on site (i.e. in side menus, in edito pages…)

![img600](../img/img600.png)

## **Service**

Service **GET /api/v1/accounts/{id}/sfic-et-vous-redirect** is triggered
when accessing /sfic-redirect (for eligible Users only).

Test User : VI\_FAAAAKJM // PLAFONDSCONCEPT@YOPMAIL.COM

*Parameters :*

-   accountId

-   websiteId

*Response :*

Auto-login URL is returned, example : 

"[*https://sficetvous.edendemo.com/connexionsso.php?token=eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJtVWRpdzJyOEVycGxDNVVMT2RVWlB3PT0iLCJpc3MiOiJzZmljIiwiaWF0IjoxNTU4MzU2ODEyLCJleHAiOjE1NTgzNTY5MzJ9.UQsoIXlJHunajaHm8bJ74A\_cZ2KLekxro8BnWFBnG6s*](https://sficetvous.edendemo.com/connexionsso.php?token=eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJtVWRpdzJyOEVycGxDNVVMT2RVWlB3PT0iLCJpc3MiOiJzZmljIiwiaWF0IjoxNTU4MzU2ODEyLCJleHAiOjE1NTgzNTY5MzJ9.UQsoIXlJHunajaHm8bJ74A_cZ2KLekxro8BnWFBnG6s)"


# **Errors management**

Assuming that 400 (except at authentication), 401, 403 and 500 errors are managed during Drupal / DSL integration and QA phases for user experience purposes (i.e: Drupal shouldn’t produce 400 “Bad Request” response, nor should call a service while being not authorized to), thus shouldn’t occur on live environments, we will focus on user-centric and data-centric errors (422 mostly).

If these types of errors still (400, 401, 403, 500) come to happen, we’ll display a generic error message : 
```
Une erreur est survenue. Nous sommes désolés pour la gêne occasionnée et vous invitons à contacter notre service Internet si le problème persiste.
```
Text is translatable from Translate Interface. 

We will also include in this story all english error messages / labels translation. Please plan to send us all english strings included whether in the translation interface (so that whitefront default labels will be french) or PHP-side, as soon as possible for us to translate them and send them back for implementation.

| Error Description                                                                                           | Service                                      | Message                                                                                                                                                                                                                                                  | Key                                                           | JSON                                                                                                                                                                                                                                                                                                                       |
| ----------------------------------------------------------------------------------------------------------- | -------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Authentication**<br>Bad credentials                                                                           | **/impulse-oauth2-service/**                     | Le login et / ou le mot de passe que vous avez saisi sont incorrects.                                                                                                                                                                                    | invalid\_grant                                                | 400 Bad Request<br>{<br>   "error": "invalid\_grant",<br>   "error\_description": "Bad credentials"<br>}                                                                                                                                                                                                                   |
|  |
|  |
|  |
|  |
| **Registration**<br>Users did not click on the validation link after registration                               | **/impulse-oauth2-service/**                     | Il semble que votre inscription n’ait pas été finalisée via le lien de confirmation de création de compte envoyé par email. Si le lien n’est plus valide, vous pouvez utiliser la fonctionnalité “Mot de passe oublié” pour compléter votre inscription. | invalid\_grant                                                | 400 Bad Request<br>{   <br>  "error": "invalid\_grant",<br>  "error\_description": "User account is locked"<br>}                                                                                                                                                                                                           |
|  |
|  |
|  |
|  |
| **Invoice Registration**<br>Already existing account                                                            | **POST /accounts/register-from-customer**        | Un compte Internet est déjà associé à l’adresse email renseignée. Veuillez vous connecter à votre espace pro via le formulaire de login ou utilisez une autre adresse email.                                                                             | email.already.in.use                                          | {<br>   "url": "http://10.0.3.245:8087/api/v1/accounts/register-from-customer",<br>   "code": 422,<br>   "message": "Unprocessable Entity",<br>   "errors": \[<br>       {<br>           "key": "email.already.in.use",<br>           "message": "Email already in use."<br>       }<br>   \]<br>}                         |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
| **Invoice Registration**<br>Mismatch in submited invoice data (amount, agency, customer code)                   | **POST /accounts/register-from-customer**        | Veuillez vérifier la cohérence des informations de votre facture (code client, agence, montant) et essayez à nouveau.                                                                                                                                    | unknown.error<br>invoice.amount.not.match<br>agency.not.match | {<br>   "url": "http://10.0.3.251:8087/api/v1/accounts/register-from-customer",<br>   "code": 422,<br>   "message": "Unprocessable Entity",<br>   "errors": \[<br>       {<br>           "key": "unknown.error",<br>           "message": "Unknown error."<br>       }<br>   \]<br>}                                       |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
| **Email / SMS Registration**<br>Contact email not found<br>Contact phone not found<br>Contact is not active<br> | **POST /accounts/register-from-contact-request** | Nous ne sommes pas en mesure de procéder à votre inscription. Veuillez choisir un autre mode d’inscription ou vous rapprocher de votre agence.                                                                                                           | customer.not.found                                            | {<br>   "url": "http://10.0.3.251:8087/api/v1/accounts/register-from-contact-request",<br>   "code": 404,<br>   "message": "Not Found",<br>   "errors": \[<br>       {<br>           "key": "customer.not.found",<br>           "message": "Customer does not exist."<br>       }<br>   \]<br>}                            |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
| **Email / SMS Registration**<br>Contact is already linked to one online account                                 | **POST /accounts/register-from-contact-request** | Un compte Internet est déjà associé à ces coordonnées. Veuillez vous connecter à votre espace pro via le formulaire de login ou utilisez une autre adresse email.                                                                                        | contact.already.linked                                        | {<br>   "url": "http://10.0.2.155:8087/api/v1/accounts/register-from-contact-request",<br>   "code": 422,<br>   "message": "Unprocessable Entity",<br>   "errors": \[<br>       {<br>           "key": "contact.already.linked",<br>           "message": "This contact is no longer available."<br>       }<br>   \]<br>} |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
| **Any service**                                                                                                 |                                              | Une erreur est survenue. Veuillez essayer à nouveau ultérieurement ou contactez notre service Internet.                                                                                                                                                  | Any error                                                     |                                                                                                                                                                                                                                                                                                                            |
| **Get wishlists List**                                                                                          | **GET /wishlists**                               | Une erreur s’est produite lors de la récupération de vos listes de produits favoris. Merci de réessayer ultérieurement.                                                                                                                                  | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **Create new wishlist**                                                                                         | **POST /wishlists**                              | Une erreur s’est produite lors de la création de la nouvelle liste. Merci de réessayer ultérieurement.                                                                                                                                                   | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **Edit wishlist Name**                                                                                          | **PATCH /wishlists/{id}**                        | Une erreur s’est produite lors de la mise à jour du nom de votre liste. Merci de réessayer ultérieurement.                                                                                                                                               | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **Get wishlist details**                                                                                        | **GET /wishlists/{id}**                          | Une erreur s’est produite lors de la récupération de votre liste de produits favoris. Merci de réessayer ultérieurement.                                                                                                                                 | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **Update articles quantities in Wishlist**                                                                      | **PUT /wishlists/{id}/articles**                 | Une erreur s’est produite lors de la mise à jour de votre liste de produits favoris. Merci de réessayer ultérieurement.                                                                                                                                  | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **Delete articles from Wishlist**                                                                               | **DELETE /wishlists/{id}/articles**              | Une erreur s’est produite lors de la suppression du produit de la liste. Merci de réessayer ultérieurement.                                                                                                                                              | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **Delete wishlist**                                                                                             | **DELETE /wishlists/{id}**                       | Une erreur s’est produite lors de la suppression de votre liste. Merci de réessayer ultérieurement.                                                                                                                                                      | If code is != from 200                                        |                                                                                                                                                                                                                                                                                                                            |
| **<del>Add product to wishlist</del>**                                                                                     | **<del>POST /wishlists/{id}/articles**</del>                | <del>Une erreur s’est produite lors de l’ajout à votre liste. Merci de réessayer ultérieurement.”</del>                                                                                                                                                             | <del>If code is != from 200</del>                                        |                                                                                                                                                                                                                                                                                                                            |

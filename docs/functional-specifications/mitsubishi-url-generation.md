# **Mitsubishi URL generation**

Mitsubishi is a Partner Brand, that has its own Spare Parts purchasing
application. From Whitefront, Users would be redirected to that
dedicated transactional application, in order to ask for a Mitsubishi
spare parts quote.

The URL which will redirect customers will be dynamic for the third
party to retrieve users' information from Whitefront website. The
provider will then provide the URL to submit.

In terms of context, contributors will set up that link on a Simple
page, which will be only accessible to VI CLI Users.

Mitsubishi entry point URL : ../mitsubishi-redirect

Process is the following :

1.  **When User access the page where Mitsubishi URL is inserted, Drupal
     will call : **

```
curl -X POST \
http://espace-pro.projects.clever-age.net/espacepro/api/encryption/?token=ce82559798bc9fbd02afc9da5eeedb5b&key=CP98765432198765&text=%3C%3Fxml%20version%3D%221.0%22%20encoding%3D%22UTF-8%22%20standalone%3D%22yes%22%3F%3E%3Ccontent%3E%3Cclient%3E%3Cc_company%3EDEMO%20INTERNET%20CLIM%20%3C%2Fc_company%3E%3Cc_email%3Emathieu.taran%40saint-gobain.com%3C%2Fc_email%3E%3Cc_firstname%3EDEMO%3C%2Fc_firstname%3E%3Cid_client%3ESAAADQGE%3C%2Fid_client%3E%3Cc_lastname%3EDEMO%20INTERNET%20CLIM%20%3C%2Fc_lastname%3E%3C%2Fclient%3E%3Crequest%3E%3Cid_req%3Ee2a6d174c0%3C%2Fid_req%3E%3C%2Frequest%3E%3C%2Fcontent%3E' \
-H 'cache-control: no-cache'

TOKEN = ce82559798bc9fbd02afc9da5eeedb5b (static)
KEY = CP98765432198765 (static)
TEXT = encoded xml :
```

```
<content>
<client>
<c_company>company.name</c_company>
<c_email>email</c_email>
<c_firstname>firstName</c_firstname>
<id_client>customer.idVEGA</id_client>
<c_lastname>lastName</c_lastname>
</client>
<request>
<id_req>UUID.randomUUID()</id_req>
</request>
</content>
```

**!!** TOKEN and KEY must be configurable from settings.inc.

2\.  **Next response is received :**

```
{ "encryptedText": "F4XIhkImjCjtGiAafqgPjun/i4lqyxaQtT2waB3Mu76sy7OJzGUuduVmOondf5qqmVkoJ38ASiJDjMNnRYy+HaNRjsQwnaxqES3zmTn8M8k68R8B96xVKo39sbTZ3e/1cg8sV4YIQ0EgLGXn8vHs27afzmkdJa/6ru4Bh2VghfDxobqb3hJQe5HAuNiQpHXP4uKLdbwhTE9XOG0ET7jJMNKlrFnej12VKm1DwogqPqm/vfwIDXNBx0plUARfiJLOITatndvDhOmrKE43s3xQlqPHAGAvG2+MzvXdtXp0satjgfKCYmbg0jcZJ0nER6yhXrjnS1Vg/tZaf2ytRbi3wGb1JQuqf7wuN8kQN9BjC8cXZaNbyKHPfM+UMS7P7W3J6DpBE74oMjcoGW0tEMebivNeeupHowVnXk6Mn5DGgTghQgol+RlqnJwmgeUHPsxA", "md5": "916e1939b736a3bac61628a6fd6d6da3" }
```

3\.  **URL gets generated, using response info :**

http://espace-pro.projects.clever-age.net/espacepro/front-office/demande-devis?ID=?KEY=?MESSAGE=?

-   ID = CP98765432198765 (static) =&gt; corresponds \[key:value\] from
     settings.inc

-   KEY = response.md5

-   MESSAGE = response.encryptedText



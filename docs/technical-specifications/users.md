# **Users** 
## **Roles**
Following Admin role will be implemented on the website :

- **Website Administrator** : this role has full rights over the website, and will only be restricted regarding sensitive parts of the back-office, such as modules configuration for example (to prevent from any wrong action that could break the website)

Note : UID 1 is not described, and is used only by development team. 

Following User roles will be implemented on the website :

Those user roles are assigned to User based on information received from services (contained in token):

| Value from Service | Role to be assigned to User |
| ------------------ | --------------------------- |
| INET               | Customer (VI)               |
| LEGACY             | Vega Customer (VI CLI)      |

- **Anonymous user (VA)** 


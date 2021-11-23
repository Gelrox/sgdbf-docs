# **Visibility block**

When an element is role-sensitive, a visibility block will be displayed
in BO. Admins and contributors can select for which roles content can be
displayed on the website.

If the checkbox is checked, the corresponding role will see the content.

Available visibility roles are the following ones :

- VA

- VAR

- Client PART

Content will be visible for users that are ONLY part. Not collab, not
something else on top of PART

- Client PRO

Content will be visible for users that are ONLY pro. Not CLUB, not
something else on top of PRO

- Client CLUB

Content will be visible for users that are CLUB, but not for only PRO
users.

- CLI (PART+PRO)

 **Note** : This visibility role could not be deleted because otherwise
 existing content visibility will have been lost

Content will be visible for users that are ONLY part OR Only PRO. Not
CLUB, not Collab.

- Collaborateur (Part user + COLLAB)

Content will be visible for users that are Collaborateur, but not for
only PART users.

Collab role is provided by WS on CustomerDto. A flag has been added :
isCollaborateur (true/false).

-   If a customer is a COLLAB (isCollaborateur=true), then the user is a
     COLLAB

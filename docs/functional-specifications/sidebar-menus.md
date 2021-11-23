# **Sidebar menus**

Sidebar menus are used across the website, and built using dedicated entities. For each menu item of a menu, label and URL can be defined. Also, position of items can be managed via Drag & Drop.
On front-end, If current page is linked to a menu, then menu is displayed, and current item is highlighted.
Page parameters are ignored when we search for active menu item as page parameters by definition should specify parameters inside a page, not the different pages. I.e. /page?a=1 is same as /page and /page?bhttps://docs.google.com/document/d/1yVb5CW7FBinU3MYea7s7UHUX-8-QGAIQ-9-UV51WWdk/edit#

Note that on Whitefront, even if any URL can be set in Sidebar menus, menus will be displayed ONLY on Simple pages. 

Sidebar items are filtered based on current user’s access taking into account following set of rules

* External links (ones that starts with protocol, http:// a:// p:// etc including links to agencies and products) are always accessible
* Internal links (that starts with / ) filtered based on access unless user have permission “link to any page” (normal users do not have it)
* Internal links to pages that does not exist are not visible for anybody
* Node links (entered via autocomplete) are filtered based on access check.

Finally, it is also possible to define access level per role on menu itself via checkboxes “Available for”. By default, when creating a new menu item, all checkboxes “available for” are checked, it is then up to contributors to adjust access depending on the needs. 


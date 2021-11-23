# **Daikin third part application**

Daikin is a third-part application that allows to visualize Products
spare parts. It requires a login / password to be accessed : credentials
are the same for all Users (there is no User-specific login context).

Only VI CLI / VI CLI CLUB can use the Daikin redirect mechanism.

Daikin URL can be inserted - for example - in a Simple page, and
clicking on it will open Daikin site in a new tab, with credentials
passed in the request so User can be logged in on the “shared account”.

Login and password must be editable via settings.inc.\
\
Login : acsweb

Password : 20190116a

URL : http://gsdb.ds-navi.co.jp/gsdb/login.asp

Example of the hidden Credentials form submit when accessing the Daikin
URL :

```
<html>
<body>

		<form name="F_Login" action="http://gsdb.ds-navi.co.jp/gsdb/login.asp" method="post" target = "_blank">
			<input name="F_Id" value="acsweb" type="hidden">
			<input name="F_Pass" value="20190116a" type="hidden">
			<input name="T_Lang" value="1" type="hidden">
		</form>
		
		<a href="javascript:document.forms[0].submit()">VALIDER</a>
	
</body>
</html>
```

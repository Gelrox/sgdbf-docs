# **Prices source for anonymous Users** 

A setting (defined in settings.inc) allows to select what is product prices source for anonymous Users, per website. 
The 2 possible options are :

* From */pricing* service (using AJAX requests)
* From *articleDTO* :
	* Use **publicPrice** value, multiply it by tax rate (since publicPrice value is without taxes, and for anonymous Users, prices must be displayed with taxes included). 
	* Note that it will also be an AJAX request - but no call to /pricing service. 

<span style="colo:red">!!<span> Note that this option does NOT apply to logged in Users.

<del>Update Release-1.08 :</del>

<del>It must be possible to define Price source independently for VA and for VAR. For example, next configuration could be applied :</del>

* <del>For VA Users, use publicPrice values</del>
* <del>For VAR Users, use prices from /pricing</del>

# **Add to Cart permission**

Add to Cart permission is not granted to Users in some cases, described below. When Add to Cart permission is not granted, then :

* User can’t add any products to the Cart
* User can’t use mass Add to Cart (from passed orders, delivery notes, Wishlists, Bulk add to Cart, Quick add to Cart widget)
* User can’t change quantities (wishlists, Cart, product detail…)

Add to Cart permission **is granted** as long as :

* User has a Cart (from service side)
* User is not logged in as ATC User (see related section for details)
* **cart.deliveryOptions** is not empty 
* In case **cart.paymentOptions** is empty, but cart.outstandingsLimit > 0

The 2 last rules can be summarized as following : 

* **cart.deliveryOptions** is empty => **DENY ADD TO CART**
	* Else
		* **cart.outstandingsLimit** > 0 and **cart.paymentOptions is empty** => **ALLOW ADD TO CART**
			* Else
				* **cart.paymentOptions is empty** => **DENY ADD TO CART**
					* Else
						* **ALLOW ADD TO CART**


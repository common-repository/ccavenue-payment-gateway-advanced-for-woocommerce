=== CCAvenue Payment Gateway Advanced for WooCommerce ===
Contributors: aheadzen
Donate link: http://example.com/
Tags:  ccavenue, iframe, payment gateway, embed
Requires at least Wordpress: 3.0.0
Tested up to Wordpress: 4.0
Tested up to WooCommerce: 2.1.0
Stable tag: 1.0.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html


Allows you to use CCAvenue payment gateway with the WooCommerce plugin.

== Description ==

Extends WooCommerce with CCAvenue Indian payment gateway. Collect card credentials and accept payments on your checkout page using our secure iFrame. Reduce payment hops and allow customers to make secure payments without leaving your web page(checkout page) for a seamless brand experience.
Also integrated sandbox settings, payment gateway name change, description/help change. and many more...

Visit [http://aheadzen.com/?p=5342]
== Installation ==
1. You should have latest version of WooCommerce plugin installed
2. Unzip and upload plugin folder to your /wp-content/plugins/ directory  OR Go to wp-admin > plugins > Add new Plugin & Upload plugin zip.
3. Go to wp-admin > Plugins(left menu) > Activate the plugin

== Screenshots ==
1. WooCommerce payment gateway setting page
2. CCAvenue Advanced setting page
3. Checkout Page Payment gateway listing
4. CCAvenue Payment Gateway Advanced - on client checkout page without going to ccavenue site.


== Configuration ==

1. Visit the WooCommerce settings page, and click on the Payment Gateways/Checkout tab.
2. Click on CCAvenue iFrame to edit the settings. If you do not see CCAvenue iFrame in the list at the top of the screen make sure you have activated the plugin in the WordPress Plugin Manager.
3. Enable the Payment Method, name it Credit Card / Debit Card / Internet Banking (this will show up on the payment page your customer sees), add in your merchand id and working key and select Iframe/Redirect Payment. Click Save.


== Changelog ==

= 1.0.0.0 =
* Fresh Public Release.

= 1.0.0.1 =
* Default address, city, state, country , zip and phone number added in case of user not added while checkout so ccavenue get the default value and continue payment.

= 1.0.0.2 =
* Added option to convert any of currency to INR for ccavenue to work.
  -- You should use WooCommerce Currency Switcher Plugin to enable multiple currency in your site.

 = 1.0.3 =
* Success response display "1" instead of complete the order - ERROR - SOLVED
--> it is changed the plugin file name to index.php - because of file name not found for notification url, it was not working.
Now it is working OK.

 = 1.0.4 =
* CCavenue payment success redirect url was wrong(Redirecting to my account page) - SOLVED
	-- now it will redirected on order success page so you can manage order tracker system. 
	
= 1.0.5 =
* Warnings and Notices removed.
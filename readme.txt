==== PayPal Website Payments Pro for WooCommerce ====
Contributors: nazrulhassanmca
Tags: woocommerce paypalpro plugin,woocommerce addon paypalpro,website payment pro for woocommerce,PayPalPro REST api,woocommerce paypalpro wordpress plugin,paypalpro refunds payments,credit card payment paypalpro,paypal credit card gateway woocommerce,paypal refunds woocommerce,paypalpro rest api credit card payment,PayPal Payment Pro woocommerce plugin,paypalpro authorize capture void refund
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_xclick&business=nazrulhassan@ymail.com&item_name=Donation+PaypalProCC+Woocommerce+Addon
Requires at least: 4.0 & WooCommerce 2.2+
Author: nazrulhassanmca
Tested up to: 4.5.3 & Woocommerce 2.6.3
Stable tag: 1.0.2
License: GPLv2

== Description ==
This plugin acts as an addon for woocommerce to add a payment method for WooCommerce for accepting credit card payments by merchants directly on your checkout page via PayPal Paments Pro.**PayPal Pro** is only available to holders of a **PayPal Pro merchant account**.This Plugins uses **REST API** to communicate to paypal to handle payments But It does not ship REST API PHP SDK bundled with plugin this plugin directly makes a CURL call to create Access tokens & Charge the cards.

= Features =
1. Very Simple Clean Code plugin to add a PayPal Website Payments Pro(WPP) method to woocommerce
2. No technical skills needed.
3. Prerequisite visualized on screenshots.
4. Adds Charde Id and Charge time to Order Note.
5. Can be customized easily.
6. Can work with test/sandbox mode.
7. It does not needs SSL.
8. Single checkbox to put it in live/test mode.
9. This plugin does not store **Credit Card Details**.
10. This plugin is designed to work **Only On REST API**
11. Single checkbox to put it in Authorize or Authorize & Capture.
12. This plugin Support to accept card types with dynamic card logo at checkout.
13. This plugin does support Refunds in woocommmerce interface
14. This plugin does support Capture in woocommmerce interface **BUT** it will only cature the initially authorized amount if your order total increases somehow its going to fail.
15. The Transaction details array returned from gateway are added to post meta of wordpress. 
16. Accept both debit and credit cards directly from your site.

== Screenshots ==

1. Screenshot 1 - Api Key Location 
2. Screenshot 2 - Admin Settings of Addon
3. Screenshot 3 - Checkout Page Form
4. Screenshot 4 - Admin panel view of order and messeges in order notes.
5. Screenshot 5 - Service Avalaible Countries
== Installation ==

1. Upload 'paypalpro-woocommerce-addon' folder to the '/wp-content/plugins/' directory
2. Activate 'PayPal Pro Credit Cards WooCommerce Addon' from wp plugin lists in admin area
3. Plugin will appear in settings of woocommerce
4. You can set the addon settings from wocommmerce->settings->Checkout->PayPal Pro Cards Settings 
5. You can check for Testing Card No 4446283280247004,Exp 11 / 2018 , CVV 874

== Frequently Asked Questions ==
1. You need to have woocoommerce plugin installed to make this plugin work
2. You need to follow The Screeenshot 1 to obtain API keys from PayPal
3. This plugin works on test & live api keys. 
4. This plugin readily works on local.
5. This plugin does not requires SSL.
6. This plugin does not store Card Details anywhere.
7. This plugin requires CURL OpenSSL installed 
8. This Plugin will only work for **PayPal Pro merchant account** In supported Countries
9. For country support please check Screeenshot tab
10. This plugin currently supports USD,CAD,EUR,JPY & GBP based on store base currency.
11. This plugin does not support Pre Order or Subscriptions however you can contact me to add PreOrder feature exclusively.
12. This plugin support Refunds in woocommmerce interface
13. Paypal Servers sometimes throw Internal Service Error during testing Multiple times with test credit card No. In that case try changing Card No. This may be due to different location of Buyer(This Point Is for TEST MODE Only)
14. Unable to refund in Non USD currency : The original transactions were run in Other Currency like (JPY), but you don't have a JPY balance in your PayPal account -- hence, all of the transactions you've run in JPY are sitting in 'unclaimed' status

See Below for REST API Supported Countries

	1. https://developer.paypal.com/docs/integration/direct/rest_api_payment_country_currency_support/#direct-credit-card-payments



== Changelog ==
2015.09.24 - Version 1.0.2
	
	1. Added default credit card form
	2. Added feature to capture authorized transaction from woocommerce order page
	3. Added Support for other Base currency like USD,CAD,EUR,JPY & GBP if store base currency is different this gateway will not be visible
	4. Added a feature to hide Payment form if no app id/secret key have been added.

2015.08.24 - Version 1.0.2

	1. Added support for dynamic card logo at checkout
	2. Fixed Refunds & Void BUG in live mode.

2015.06.04 - Version 1.0.1

	1. Added Support for Refunds(In case of auth & captured) Void(for Authorized Transaction) Within WooCommerce Interface.
	2. Added support to accept card types
	3. Added support for authorize or authorize & capture
	4. Added performance improvement and bugfixes
	5. Added Bugfix to store access token to database due to its long validity of 8 Hrs
	6. Fixed Warnings from Debug mode set to true on wordpress.
	7. Added charge id to payment complete so it adds a postmeta for charge id.
	
2015.05.06 - Version 1.0.0

	1. First Release

== Upgrade Notice == 
This is first version no known notices yet

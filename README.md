=== 1stPayGateway Payment Gateway for WooCommerce ===
Contributors: demourak
Tags: 1stPayGateway, gateway, woocommerce, plugin, processing, payment, credit card, merchant, checkout, goEmerchant
Requires at least: 4.5.3
Tested up to: 4.7
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Accept credit cards through your WooCommerce store. Supports customer information management, refunds, subscriptions, and more.

== Description ==

= Features =

* Supports automatic refunds from the WordPress Dashboard
* Customers can save credit card information to use for future orders
* Customers can edit saved credit cards from their "My Account" menu
* Supports both "Authorize Only" and "Authorize & Settle" transaction types
* User credit cards are securely stored.
* Supports WooCommerce Subscriptions 2.0 and later 
* Allows customers to change the payment method for their subscription
* Uses the WooCommerce built-in checkout, allowing the customer to remain on your site

= Using the Plugin =

* This plugin requires a 1stPayGateway merchant Account. Call 888-638-7867 for assistance.
* Once installed, navigate to WooCommerce -> Settings -> Checkout -> 1stPayGateway, and enter your account information. Click "Save Settings".

== Installation ==

= Automatic Installation =

1. On your WordPress dashboard side menu, navigate to Plugins --> Add New.
2. Search for "1stPayGateway Payment Gateway for WooCommerce" and click "Install Now"
3. Activate the plugin from the Plugins page.

= Manual Installation =

1. Download the plugin's zip folder. 
2. On your WordPress dashboard side menu, navigate to Plugins --> Add New.
3. Click "Upload Plugin".
4. Your computer's file browser will appear. Use it to select the plugin's zip folder.

OR

1. Download the plugin's zip folder. 
2. Save the plugin folder to the `/wp-content/plugins/` directory
3. Activate the plugin through the 'Plugins' menu in WordPress.

Configure gateway settings in WooCommerce --> Settings --> Checkout --> 1stPayGateway

== Frequently Asked Questions ==

= How do I get a 1stPayGateway Merchant account? =

Call 888-638-7867, and one of our sales representatives will be happy to assist you.

= How do I get my Gateway ID and Processor ID? =

Login to the Transaction Center with your Transaction Center ID, username and password. Then follow the steps in [this article](http://support.goemerchant.com/transaction-center.aspx?article=gateway-options) to access your gateway credentials.
If after following these steps you still have trouble, contact our support department at support@goemerchant.com or 888-417-8729

= How do I test the plugin before going live? =

Call 888-638-7867 and request a sandbox account for WooCommerce. You will be provided credentials that you can enter in your Plugin Settings to configure the plugin to your test account.

= What does the "Authorize Only" option do? =

If you enable the "Authorize Only" setting, funds from transactions that are approved will not automatically be transferred. 
So submit a transaction processed as an Authorize-Only, you must sign into the Transaction Center and manually mark the transaction as settled.
Transactions processed as "Authorize-Only" are automatically voided after 10 days if they are not submitted for settlement.

== Screenshots ==

1. Checkout
2. Customer's "My Account" page with stored credit cards
3. Settings
4. "Thank you" page

== Changelog ==

= 1.0.0 =

* Initial Release
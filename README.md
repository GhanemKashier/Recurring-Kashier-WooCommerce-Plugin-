# Recurring-Kashier-WooCommerce-Plugin-


### Wordpress Woocommerce  - Kashier plugin

 * WC requires at least: 2.6
 * WC tested up to: 8.5.0

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/woocommercew-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service.

- Embedded form integration.

- Connected accounts 

- Supports [Woocommerce subscriptions](https://woocommerce.com/products/woocommerce-subscriptions/) payments and tokenization.

- 3D secure cards authentication support.

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.

- Customer could save and manage their cards for future payments.



### Installation

- Download kashier.zip https://github.com/Kashier-payments/Kashier-WooCommerce-Plugin/archive/refs/heads/master.zip

- Upload and activate the plugin on Woocommerce.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-1-installPlugin.png)

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-2-activate.png)

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > Payment API keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/apikey_mid_test.png)

- Insert the MID and Test Api Key in the Configuration page of the module.

- Make sure the test mode is on.

- Customize the title and description that will show up tp your users.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-4-settings.png)


### Test plugin 

- Proceed to make an order on your shop, a new payment method is added "Pay by card". it could be changed from module configuration.

- After proceeding you will find a Kashier "pay by " button, fill in the test card and proceed to make a payment.

- Test card 5111 1111 1111 1118 - 06/22 - 100

- Test 3dsecure card 5123 4500 0000 0008 - 06/22 - 100

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-5-pay.png)


### Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > Payment API keys 

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/apikey_mid_live.png)

- Insert Live Api Key in the Configuration page of the module.

- Remove the test mode check.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-7-live-kashier-n.png)

### Connected account

- Make sure the connected account is on.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-8-live-kashier-n.png)

- Navigate to [plugin folder -> connected-account folder -> connected_account.txt file ](https://github.com/Kashier-payments/Kashier-WooCommerce-Plugin/blob/master/connected-account/connected_account.txt)

      1. Insert the name of checkout custom field in the first line
      2. Insert the value of field and connected account as pattern `branch-1 | MID` to map values to connected accounts MID


### Card management

- Add or select a payment method

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-add-payment-method.png)

- Manage payment methods

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-Plugin/master/steps/install-manage-methods.png)


### Support

- Leave us an inquiry ticket on support@kashier.io for questions.



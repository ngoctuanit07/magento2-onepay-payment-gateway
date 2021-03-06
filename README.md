# OnePay Payment Gateway for Magento 2
In this module, I integrated two payments gateway of OnePay, that is Domestic ATM Card and International Card.

## How to install this extension?
 + Under the root of your website, please run the command lines bellowing:
    - Before installing this extension, make sure that you have installed the PHPCuong_Core module, If you don't install this module yet, please install it by running the command line: **composer require php-cuong/magento2-module-core**
    - Install the PHPCuong_OnePay module:
    - **composer require php-cuong/magento2-onepay-payment-gateway**
    - **php bin/magento setup:upgrade**
    - **php bin/magento setup:static-content:deploy**
    - **php bin/magento setup:di:compile**
    - **php bin/magento indexer:reindex**
    - **php bin/magento cache:flush**

## How to see the results?

### - On the Backend:
- Go to the Admin Panel of the Magento Store and navigate to the GiaPhuGroup → OnePay Payment Gateway → Configuration
- The configuration information:
    + International card: https://mtf.onepay.vn/developer/?page=modul_quocte
    + Domestic card: https://mtf.onepay.vn/developer/?page=modul_noidia

### - On the Storefront:
- Add a product to shopping cart.
- Go the the checkout page.

## The screenshot of this extension

### - On the Storefront:

![ScreenShot](https://github.com/php-cuong/magento2-onepay-payment-gateway/blob/master/Screenshot/domestic-atm-card.png)
#### *The OnePay payment gateway - Domestic ATM card*

![ScreenShot](https://github.com/php-cuong/magento2-onepay-payment-gateway/blob/master/Screenshot/international-card.png)
#### *The OnePay payment gateway - International card*

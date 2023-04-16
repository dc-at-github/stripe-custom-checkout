# CREATE CUSTOM CHECKOUT PAGE WITH STRIPE

* Requirements

You need composer install on your system/server

to install require streipe packages. you need to execute the following composer command opening project directory in CLI.

> composer require stripe/stripe-php

* secrets.php

This file contains secrets.php file. you have to assign strip secrete key to the $stripeSecretKey variable.

You can get stripe secret key and Stripe public key on the developer dashboard home page. For that you can refere Stripe developer documentation.

* Checkout.js

You have to assign stripe public key to stripePublicKey variable defined in this file.

You can test the checkout process with the following URL.

http://[YOUR-DOMAIN-NAME]/checkout.html

replace YOUR-DOMAIN-NAME with your domain name.

for Example: 

* http://localhost/checkout.html
* http://mysite.com/checkout.html
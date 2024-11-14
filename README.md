# SSL Commerz Gateway

[![Build Status](https://travis-ci.org/blesta/gateway-sslcommerz.svg?branch=master)](https://travis-ci.org/blesta/gateway-sslcommerz) [![Coverage Status](https://coveralls.io/repos/github/blesta/gateway-sslcommerz/badge.svg?branch=master)](https://coveralls.io/github/blesta/gateway-sslcommerz?branch=master)

This is a nonmerchant gateway for Blesta that integrates with [SSL Commerz](https://www.sslcommerz.com/).

## Install the Gateway

1. You can install the gateway via composer:

    ```
    composer require blesta/sslcommerz
    ```

2. Upload the source code to a /components/gateways/nonmerchant/sslcommerz/ directory within
your Blesta installation path.

    For example:

    ```
    /var/www/html/blesta/components/nonmerchant/sslcommerz/
    ```

3. Log in to your admin Blesta account and navigate to
> Settings > Payment Gateways

4. Find the SSL Commerz gateway and click the "Install" button to install it

5. You're done!

### Blesta Compatibility

|Blesta Version|Module Version|
|--------------|--------------|
|< v4.9.0|v1.1.1|
|>= v4.9.0|v1.2.0|

# PHP - Stripe Integration example

This is a streamlined/minimalistic version of the official [Stripe](https://stripe.com/) 
PHP example that can be found [here](https://github.com/stripe-samples/checkout-one-time-payments).

You need a Stripe account and test API keys. Please refer to the official Stripe documentation.

## Requirements
* PHP 

## How to run

1. Run composer to set up dependencies

```
composer install
```

2. Copy config.ini.sample to config.ini and replace with your Stripe API keys 

```
cp config.ini.sample config.ini
```

3. Run the server locally

```
cd public
php -S localhost:4242
```

4. Go to localhost:4242

# wordpress-integrartion-tests

## How to run cypress tests

### Prerequisites

* WordPress and the WooCommerce plugin should be installed with the default storefront theme
* WooCommerce sample data for products imported to the store
* Credit Card should be configured

### Steps

* Install dependencies `npm i`
* Update "cypress/fixtures/config.json"
* Execute `./node_modules/.bin/cypress run` in the terminal to run all the tests
---
title: "Lulu Dropshipping Plugin"
date: 2023-04-09T22:04:11-04:00
---

#### Sell any book from your [WordPress](https://www.wordpress.com) site powered by [WooCommerce](https://woocommerce.com)

This project initially began to help a close friend of mine.
He started an independent publishing company 
*[Taurus Necrus](https://www.taurusnecrus.com)* and was initially creating
listings for his books for sale on [Lulu's](https://www.lulu.com/shop) book
store. As time went on, however, the advantage of running his own website became
clear and he was wondering if it was possible to sell the books using Lulu as a
drop-shipper. Herein lies the genesis of this WordPress/WooCommerce plugin.

## Features
* Sell self-published books from your own website
* Automatically print new orders on-demand and ship directly to customer
* Pass shipping costs directly to customer *(optional)*

## Disclaimer

I made this plugin a couple of years ago and was not trying to build something *really* for public use.
The environment it is being used in is highly constrained and different WordPress/WooCommerce configurations
have not been tested at all. If you are using or would like to use this plugin and need some help, feel free
to reach out to me via [email](mailto:brett@techneosis.com)


#### Download the latest version here:

[{{< inTextImg url="/images/get-it-on-github.png" height="50">}}](https://github.com/Techneosis/wc-lulu-fulfillment)


## Changelog

### 1.4.0

* Run an order at print cost from the admin edit order page!
    1. Updates Lulu line items with printing cost
    1. Adds shipping costs from Lulu
    1. Adds fulfillment fees from Lulu

### 1.3.0

* Upload Cover and Interior PDFs directly on the product page now - no more copy-pasting links!
* See Lulu production status of an order from the "Orders" list
* When a Lulu book product is updated:
    1. Verify binding options are printable by Lulu
    1. Calculate print cost
    * Lulu requires an address to calculate print cost. Defaults to store address set in WooCommerce settings, can be overridden in options

### 1.2.0

* Shipping Option! Enable Lulu Shipping Method in the plugin settings
    * Lulu fulfilled items will be packaged together and user will be charged Lulu's shipping price directly
    * Options for Package name and shipping fee label, call it whatever you like!

### 1.1.0

* Orders containing Lulu products are checked hourly until completed, Updated with current Lulu fulfillment status. Possible statuses are:
    1. ```UNPAID```
    1. ```PAID```
    1. ```PRODUCTION READY``` 
    1. ```IN PRODUCTION```
    1. ```SHIPPED```
* Configuration option to automatically mark orders containing Lulu products complete if:
    1. The order only contains products fulfilled by Lulu
    1. The order has been shipped by Lulu

### 1.0

* Initial Version. Create Lulu Book products in your WooCommerce store and have them automatically printed and shipped to your customers once payment is received.


## Screenshots
### Plugin Configuration
{{< inTextImg url="/images/lulu-plugin/plugin-settings.png" height="400" >}}
### Creating a *Lulu Book* Product
{{< inTextImg url="/images/lulu-plugin/product-config.png" height="600" >}}
### Shipping Costs decided by Lulu
{{< inTextImg url="/images/lulu-plugin/shipping-costs.png" height="200" >}}

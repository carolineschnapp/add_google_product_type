## What this does ##

This is an automated Ruby script that will add for you one and the same Google Product Type to all products in your Shopify shop. To use if A) You rely on Shopify to publish your products on Google Product Search B) you want to add the same Google Product Type to all the products in your shop. 

Why would you want to do that? Google Merchant Center maintains a product type taxonomy. The types listed there are the ones that Google recognizes. By specifying a custom type for your products that is selected from that list, you improve your chances for a higher rank on Google Product Search.

### Requirements ###

This script requires that you [use the shopify api gem with the credentials of a private app](http://wiki.shopify.com/Using_the_shopify_api_gem_with_the_credentials_of_a_private_app).


## Instructions ##

### STEP 1 ###

Pick your Google Product Type from that list: [The Product Type Attribute](http://www.google.com/support/merchants/bin/answer.py?hl=en&answer=160081)

### STEP 2 ###

Set the following constants and variables in the add_google_product_type.rb script:

     APIKEY = 'APIKEY'
     PASSWORD = 'PASSWORD'
     SHOPNAME = 'shopname'
     GOOGLE_PRODUCT_TYPE = 'the product type you want...'

### STEP 3 ###

Run the script using this command:

     ruby add_google_product_type.rb
     
### STEP 4 ###

Tell your girlfriend she's beautiful.

## FAQ ##

Is there any side effect in running this script several times?

_None._

I changed my mind and want to change the product type on all my products again. What do I do?

*Set the GOOGLE_PRODUCT_TYPE constant to the new value you want in the Ruby script, and run the script once more.*

Things won't explode?

_Nope._
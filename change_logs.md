# Change Logs

## [ v1.5.4 ] - 11th May 2021 - Aniket Malik
* Fixed - Sign up issue leading to Wordpress Rest No Route found issue.
* Fixed - Cart loading issue when cart item product price was badly formatted.
* Updated - Internal code enhancements to Woocommerce Flutter Package 

## [ v1.5.3 ] - 2nd May 2021 - Aniket Malik
* Fixed - Cart item error when "sold individually" flag was not set to true
 or false in woocommerce products.

## [ v1.5.2 ] - 30th April 2021 - Aniket Malik
* Improved - Apple Sign in capabilities and workflow.

## [ v1.5.1 ] - 27th April 2021 - Aniket Malik
* Added - Support for Virtual Products for downloads
* Added - showCustomerDownloadsListTile flag to hide or show downloads list
 tile in the account settings screen
* Updated - Account settings name to Account

## [ v1.5.0 ] - 23rd April 2021 - Aniket Malik
* Added - Multilingual feature, now the application can support
 multiple languages in the application.
* Added - Categories in the bottom tab bar for fast and easy access
* Added - Show a horizontal list of child categories in the bottom of the
 CategorisedProductsScreen Appbar for fast selection of child categories
* Added - "categoriesScreenCrossAxisCount" flag in Config.dart to manage number
 of columns of categories in the Category Screen
* Added - "showCategoriesHorizontalListBelowCategorisedProductsAppBar" to
 hide or show the horizontal list of child categories in the bottom of the
  CategorisedProductsScreen Appbar 

## [ v1.4.0 ] - 20th April 2021 - Aniket Malik
* Added - Show login page to guest customer to access the following screens
 -- My Orders, Profile Information, My Points, Shipping / Billing Address
 , Change Password and other screens where only authenticated customers are
  allowed.

## [ v1.3.2 ] - 13th April 2021 - Aniket Malik
* Updated - WooStore Pro Api Wordpress Plugin to be independent of Simple JWT
 login plugin and JWT Authentication for Wp-API plugin. Now this
  functionality is integrated in the native plugin.

## [ v1.3.1 ] - 12th April 2021 - Aniket Malik
* Fixed - Categories section not showing with multiple level of nested child
 categories.
* Updated - Child categories of child categories will be displayed as top
 level categories as only 1 level deep nesting of child categories is
  supported currently.

## [ v1.3.0 ] - 10th April 2021 - Aniket Malik
* Added - Now you have options to hide categories and tags list in
 home, search filter modal and all products filter modal
* Added - Show reward points in the product screen
* Added - Fetch reward points for both simple and variable products and
 variations
* Added - Buy now option with add to cart in product screen bottom to jump to
  cart directly.
* Updated - WooCommerce Flutter package Api for application
* Updated - WooStore Pro Api wordpress plugin for application
* Updated - Like button on top of product screen.
* Updated - On Sale banner animation.

## [ v1.2.1 ] - 8th April 2021 - Aniket Malik
* Fixed - Add reviews to the products. (Bug #5)

## [ v1.2.0 ] - 8th April 2021 - Aniket Malik
* Added - Support for WooCommerce Points and Rewards plugin, now the logged in
 customers can see their points balance and events from the application
  directly. 
* Added - Config Flag to hide/show the 'My Points' list tile in the 'Account
 Settings page'
* Updated - WooCommerce Api Flutter Package for the application to support
 woocommerce rewards and points plugin 

## [ v1.1.0 ] - 6th April 2021 - Aniket Malik
* Added - HTML description to Native widgets, Now you can use HTML tags in
 description to show details of your product. You can also use images which
  will be rendered Natively in the application. Add web links, email links
  , telephone links to your descriptions and they will be opened in the
   default suitable app in the mobile phone.  
* Updated - flutter woocommerce api for application

## [ v1.0.0 ] - 5th April 2021 - Aniket Malik
1. Updated - the name of the application (due to name conflict) 
2. Fixed - Guest User checkout issue (Bug #4)
3. Updated - WordPress Plugin, Now updated to - WooStore Pro Api.
4. Added - "Continue without login" button on Login Screen for Guest Customers
 Other optimisations.

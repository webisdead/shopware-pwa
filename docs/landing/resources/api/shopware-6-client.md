<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@shopware-pwa/shopware-6-client](./shopware-6-client.md)

## shopware-6-client package

## Functions

|  Function | Description |
|  --- | --- |
|  [addCartItems(items, contextInstance)](./shopware-6-client.addcartitems.md) | Adds multiple items to the cart. Accepts every type of cart item. |
|  [addProductReview(productId, productReviewData, contextInstance)](./shopware-6-client.addproductreview.md) | Add a review to specific product by its ID |
|  [addProductToCart(productId, quantity, contextInstance)](./shopware-6-client.addproducttocart.md) | Adds specific quantity of the product to the cart by productId. It creates a new cart line item.<!-- -->Warning: This method does not change the state of the cart in any way if productId already exists in a cart. For changing the quantity use addQuantityToCartLineItem() or changeCartLineItemQuantity() methods. |
|  [addPromotionCode(promotionCode, contextInstance)](./shopware-6-client.addpromotioncode.md) | Adds new promotion code to the cart by its code.<!-- -->Promotion code is being added as separate cart item line. |
|  [addWishlistProduct(productId, contextInstance)](./shopware-6-client.addwishlistproduct.md) | Add a product with a specific ID to the wishlist |
|  [cancelOrder(orderId, contextInstance)](./shopware-6-client.cancelorder.md) | Cancel an order |
|  [changeCartItemQuantity(itemId, newQuantity, contextInstance)](./shopware-6-client.changecartitemquantity.md) | Changes the current quantity in specific cart line item to given quantity.<!-- -->Example: If current quantity is 3 and you pass 2 as quantity parameter, you will get a new cart's state with quantity 2. |
|  [changeOrderPaymentMethod(orderId, paymentMethodId, contextInstance)](./shopware-6-client.changeorderpaymentmethod.md) | Change payment method for given order |
|  [clearCart(contextInstance)](./shopware-6-client.clearcart.md) | When no sw-context-token given then this method return an empty cart with the new sw-context-token.<!-- -->When sw-context-token given then this method simply returns the current state of the cart.<!-- -->As the purpose of this method is not clear we recommend to use <code>getCart</code> method because its behaviour seems to be the same. |
|  [confirmAccountRegistration(params, contextInstance)](./shopware-6-client.confirmaccountregistration.md) | Confirm an account registration in double opt-in mode |
|  [confirmPasswordReset(params, contextInstance)](./shopware-6-client.confirmpasswordreset.md) | Confirm a customer's password reset. Set new password for account. |
|  [createCustomerAddress(params, contextInstance)](./shopware-6-client.createcustomeraddress.md) | Create an address and respond the new address's id |
|  [createInstance(initialConfig)](./shopware-6-client.createinstance.md) |  |
|  [createOrder(params, contextInstance)](./shopware-6-client.createorder.md) | Creates an order for logged in and guest users |
|  [deleteCustomerAddress(addressId, contextInstance)](./shopware-6-client.deletecustomeraddress.md) | Delete's the customer's address by id |
|  [getAvailableCountries(contextInstance)](./shopware-6-client.getavailablecountries.md) | Get all available countries |
|  [getAvailableCurrencies(contextInstance)](./shopware-6-client.getavailablecurrencies.md) |  |
|  [getAvailableLanguages(contextInstance)](./shopware-6-client.getavailablelanguages.md) |  |
|  [getAvailablePaymentMethods(contextInstance, params)](./shopware-6-client.getavailablepaymentmethods.md) |  |
|  [getAvailableSalutations(contextInstance)](./shopware-6-client.getavailablesalutations.md) | Get all available salutations |
|  [getAvailableShippingMethods(contextInstance, params)](./shopware-6-client.getavailableshippingmethods.md) |  |
|  [getCart(contextInstance)](./shopware-6-client.getcart.md) | Gets the current cart for the sw-context-token. |
|  [getCategories(searchCriteria, contextInstance)](./shopware-6-client.getcategories.md) |  |
|  [getCategory(categoryId, contextInstance)](./shopware-6-client.getcategory.md) |  |
|  [getCategoryProducts(categoryId, criteria, contextInstance)](./shopware-6-client.getcategoryproducts.md) | Get default amount of products and listing configuration for given category |
|  [getCmsPage(path, criteria, contextInstance)](./shopware-6-client.getcmspage.md) |  |
|  [getCustomer(parameters, contextInstance)](./shopware-6-client.getcustomer.md) | Get customer's object |
|  [getCustomerAddress(addressId, contextInstance)](./shopware-6-client.getcustomeraddress.md) | Get the customer's address by id |
|  [getCustomerAddresses(parameters, contextInstance)](./shopware-6-client.getcustomeraddresses.md) | Get all customer's addresses |
|  [getCustomerOrders(parameters, contextInstance)](./shopware-6-client.getcustomerorders.md) | Get all customer's orders |
|  [getLandingPage(landingPageId, params, contextInstance)](./shopware-6-client.getlandingpage.md) | Fetches a landing page entity |
|  [getOrderDetails(orderId, params, contextInstance)](./shopware-6-client.getorderdetails.md) | Get order details |
|  [getPaymentMethodDetails(paymentId, contextInstance)](./shopware-6-client.getpaymentmethoddetails.md) |  |
|  [getProduct(productId, params, contextInstance)](./shopware-6-client.getproduct.md) | Get the product with passed productId |
|  [getProductReviews(productId, criteria, contextInstance)](./shopware-6-client.getproductreviews.md) | Get product reviews |
|  [getProducts(criteria, contextInstance)](./shopware-6-client.getproducts.md) | Get default amount of products |
|  [getSeoUrl(params, contextInstance)](./shopware-6-client.getseourl.md) |  |
|  [getSeoUrls(entityId, languageId, contextInstance)](./shopware-6-client.getseourls.md) | Returns an array of SEO URLs for given entity Can be used for other languages as well by providing the languageId |
|  [getSessionContext(contextInstance)](./shopware-6-client.getsessioncontext.md) | Loads session context, containing all session-related data. |
|  [getShippingMethodDetails(shippingId, contextInstance)](./shopware-6-client.getshippingmethoddetails.md) |  |
|  [getStoreNavigation({ requestActiveId, requestRootId, depth, buildTree, searchCriteria, }, contextInstance)](./shopware-6-client.getstorenavigation.md) |  |
|  [getUserCountry(countryId, contextInstance)](./shopware-6-client.getusercountry.md) |  |
|  [getUserSalutation(salutationId, contextInstance)](./shopware-6-client.getusersalutation.md) |  |
|  [getWishlistProducts(criteria, contextInstance)](./shopware-6-client.getwishlistproducts.md) | Fetch a current Wishlist with added products |
|  [handlePayment(params, contextInstance)](./shopware-6-client.handlepayment.md) |  |
|  [invokeGet({ address }, contextInstance)](./shopware-6-client.invokeget.md) | Invoke custom GET request to shopware API. Mostly for plugins usage. You can skip domain and pass only endpoint ex. <code>/api/my/endpoint</code> |
|  [invokePost({ address, payload, }, contextInstance)](./shopware-6-client.invokepost.md) | Invoke custom POST request to shopware API. Mostly for plugins usage. You can skip domain and pass only endpoint ex. <code>/api/my/endpoint</code> |
|  [login({ username, password }, contextInstance)](./shopware-6-client.login.md) | Login user to shopware instance. |
|  [logout(contextInstance)](./shopware-6-client.logout.md) | End up the user session. |
|  [mergeWishlistProducts(productIds, contextInstance)](./shopware-6-client.mergewishlistproducts.md) | Merge the current Wishlist with a products with provided IDs |
|  [newsletterSubscribe(params, contextInstance)](./shopware-6-client.newslettersubscribe.md) |  |
|  [newsletterUnsubscribe({ email, }, contextInstance)](./shopware-6-client.newsletterunsubscribe.md) |  |
|  [register(params, contextInstance)](./shopware-6-client.register.md) | Register a customer |
|  [removeCartItem(itemId, contextInstance)](./shopware-6-client.removecartitem.md) | Deletes the cart line item by id.<!-- -->This method may be used for deleting "product" type item lines as well as "promotion" type item lines. |
|  [removeWishlistProduct(productId, contextInstance)](./shopware-6-client.removewishlistproduct.md) | Delete a product with a specific ID from the wishlist |
|  [resetPassword(params, contextInstance)](./shopware-6-client.resetpassword.md) | Reset a customer's password |
|  [searchProducts(criteria, contextInstance)](./shopware-6-client.searchproducts.md) | Search for products based on criteria. From: Shopware 6.4 |
|  [searchSuggestedProducts(criteria, contextInstance)](./shopware-6-client.searchsuggestedproducts.md) | Search for suggested products based on criteria. From: Shopware 6.4 |
|  [sendContactForm(params, contextInstance)](./shopware-6-client.sendcontactform.md) |  |
|  [setCurrentBillingAddress(billingAddressId, contextInstance)](./shopware-6-client.setcurrentbillingaddress.md) | Set the current session's billing address to correspoding to id |
|  [setCurrentCurrency(newCurrencyID, contextInstance)](./shopware-6-client.setcurrentcurrency.md) |  |
|  [setCurrentLanguage(newLanguageId, contextInstance)](./shopware-6-client.setcurrentlanguage.md) |  |
|  [setCurrentPaymentMethod(newPaymentMethodId, contextInstance)](./shopware-6-client.setcurrentpaymentmethod.md) |  |
|  [setCurrentShippingAddress(shippingAddressId, contextInstance)](./shopware-6-client.setcurrentshippingaddress.md) | Set the current session's shipping address to correspoding to id |
|  [setCurrentShippingMethod(newShippingMethodId, contextInstance)](./shopware-6-client.setcurrentshippingmethod.md) |  |
|  [setDefaultCustomerBillingAddress(addressId, contextInstance)](./shopware-6-client.setdefaultcustomerbillingaddress.md) | Set address as default |
|  [setDefaultCustomerPaymentMethod(paymentMethodId, contextInstance)](./shopware-6-client.setdefaultcustomerpaymentmethod.md) | Set payment method under provided ID as default |
|  [setDefaultCustomerShippingAddress(addressId, contextInstance)](./shopware-6-client.setdefaultcustomershippingaddress.md) | Set address as default |
|  [updateCustomerAddress(params, contextInstance)](./shopware-6-client.updatecustomeraddress.md) | Update an address for specific ID |
|  [updateEmail(params, contextInstance)](./shopware-6-client.updateemail.md) | Update a customer's email |
|  [updatePassword(params, contextInstance)](./shopware-6-client.updatepassword.md) | Update a customer's password |
|  [updateProfile(params, contextInstance)](./shopware-6-client.updateprofile.md) | Update a customer's profile data |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [ClientSettings](./shopware-6-client.clientsettings.md) |  |
|  [ConfigChangedArgs](./shopware-6-client.configchangedargs.md) |  |
|  [ContactFormData](./shopware-6-client.contactformdata.md) |  |
|  [CustomerRegisterResponse](./shopware-6-client.customerregisterresponse.md) |  |
|  [CustomerResetPasswordParam](./shopware-6-client.customerresetpasswordparam.md) |  |
|  [CustomerUpdateEmailParam](./shopware-6-client.customerupdateemailparam.md) |  |
|  [CustomerUpdatePasswordParam](./shopware-6-client.customerupdatepasswordparam.md) |  |
|  [CustomerUpdateProfileParam](./shopware-6-client.customerupdateprofileparam.md) |  |
|  [GetStoreNavigationParams](./shopware-6-client.getstorenavigationparams.md) | More about the navigation parameters: https://docs.shopware.com/en/shopware-platform-dev-en/store-api-guide/navigation?category=shopware-platform-dev-en/store-api-guide |
|  [NewsletterSubscribeData](./shopware-6-client.newslettersubscribedata.md) |  |
|  [ShopwareApiInstance](./shopware-6-client.shopwareapiinstance.md) |  |

## Variables

|  Variable | Description |
|  --- | --- |
|  [config](./shopware-6-client.config.md) |  |
|  [getAddWishlistProductEndpoint](./shopware-6-client.getaddwishlistproductendpoint.md) |  |
|  [getCancelOrderEndpoint](./shopware-6-client.getcancelorderendpoint.md) |  |
|  [getCategoryDetailsEndpoint](./shopware-6-client.getcategorydetailsendpoint.md) |  |
|  [getCategoryEndpoint](./shopware-6-client.getcategoryendpoint.md) |  |
|  [getChangeOrderPaymentMethodEndpoint](./shopware-6-client.getchangeorderpaymentmethodendpoint.md) |  |
|  [getCheckoutCartEndpoint](./shopware-6-client.getcheckoutcartendpoint.md) |  |
|  [getCheckoutCartLineItemEndpoint](./shopware-6-client.getcheckoutcartlineitemendpoint.md) |  |
|  [getCheckoutOrderEndpoint](./shopware-6-client.getcheckoutorderendpoint.md) |  |
|  [getConfirmPasswordResetEndpoint](./shopware-6-client.getconfirmpasswordresetendpoint.md) |  |
|  [getContactFormEndpoint](./shopware-6-client.getcontactformendpoint.md) |  |
|  [getContextCountryEndpoint](./shopware-6-client.getcontextcountryendpoint.md) |  |
|  [getContextCurrencyEndpoint](./shopware-6-client.getcontextcurrencyendpoint.md) |  |
|  [getContextEndpoint](./shopware-6-client.getcontextendpoint.md) |  |
|  [getContextLanguageEndpoint](./shopware-6-client.getcontextlanguageendpoint.md) |  |
|  [getContextPaymentMethodEndpoint](./shopware-6-client.getcontextpaymentmethodendpoint.md) |  |
|  [getContextSalutationEndpoint](./shopware-6-client.getcontextsalutationendpoint.md) |  |
|  [getContextShippingMethodEndpoint](./shopware-6-client.getcontextshippingmethodendpoint.md) |  |
|  [getCustomerAccountConfirmEndpoint](./shopware-6-client.getcustomeraccountconfirmendpoint.md) |  |
|  [getCustomerAddAddressEndpoint](./shopware-6-client.getcustomeraddaddressendpoint.md) |  |
|  [getCustomerAddressEndpoint](./shopware-6-client.getcustomeraddressendpoint.md) |  |
|  [getCustomerDefaultBillingAddressEndpoint](./shopware-6-client.getcustomerdefaultbillingaddressendpoint.md) |  |
|  [getCustomerDefaultShippingAddressEndpoint](./shopware-6-client.getcustomerdefaultshippingaddressendpoint.md) |  |
|  [getCustomerDetailsUpdateEndpoint](./shopware-6-client.getcustomerdetailsupdateendpoint.md) |  |
|  [getCustomerEndpoint](./shopware-6-client.getcustomerendpoint.md) |  |
|  [getCustomerLoginEndpoint](./shopware-6-client.getcustomerloginendpoint.md) |  |
|  [getCustomerLogoutEndpoint](./shopware-6-client.getcustomerlogoutendpoint.md) |  |
|  [getCustomerOrderEndpoint](./shopware-6-client.getcustomerorderendpoint.md) |  |
|  [getCustomerRegisterEndpoint](./shopware-6-client.getcustomerregisterendpoint.md) |  |
|  [getCustomerResetPasswordEndpoint](./shopware-6-client.getcustomerresetpasswordendpoint.md) |  |
|  [getCustomerUpdateEmailEndpoint](./shopware-6-client.getcustomerupdateemailendpoint.md) |  |
|  [getCustomerUpdatePasswordEndpoint](./shopware-6-client.getcustomerupdatepasswordendpoint.md) |  |
|  [getCustomerUpdatePaymentMethodEndpoint](./shopware-6-client.getcustomerupdatepaymentmethodendpoint.md) |  |
|  [getGetWishlistProductsEndpoint](./shopware-6-client.getgetwishlistproductsendpoint.md) |  |
|  [getLandingPageDetailsEndpoint](./shopware-6-client.getlandingpagedetailsendpoint.md) |  |
|  [getMergeWishlistProductsEndpoint](./shopware-6-client.getmergewishlistproductsendpoint.md) |  |
|  [getNewsletterSubscribeEndpoint](./shopware-6-client.getnewslettersubscribeendpoint.md) |  |
|  [getNewsletterUnsubscribeEndpoint](./shopware-6-client.getnewsletterunsubscribeendpoint.md) |  |
|  [getPageResolverEndpoint](./shopware-6-client.getpageresolverendpoint.md) |  |
|  [getProductDetailsEndpoint](./shopware-6-client.getproductdetailsendpoint.md) |  |
|  [getProductEndpoint](./shopware-6-client.getproductendpoint.md) |  |
|  [getProductListingEndpoint](./shopware-6-client.getproductlistingendpoint.md) |  |
|  [getProductReviewsEndpoint](./shopware-6-client.getproductreviewsendpoint.md) |  |
|  [getRemoveWishlistProductEndpoint](./shopware-6-client.getremovewishlistproductendpoint.md) |  |
|  [getSearchEndpoint](./shopware-6-client.getsearchendpoint.md) |  |
|  [getSeoUrlEndpoint](./shopware-6-client.getseourlendpoint.md) |  |
|  [getStoreNavigationEndpoint](./shopware-6-client.getstorenavigationendpoint.md) |  |
|  [getStoreNewsletterConfirmEndpoint](./shopware-6-client.getstorenewsletterconfirmendpoint.md) |  |
|  [getStoreNewsletterSubscribeEndpoint](./shopware-6-client.getstorenewslettersubscribeendpoint.md) |  |
|  [getStoreNewsletterUnsubscribeEndpoint](./shopware-6-client.getstorenewsletterunsubscribeendpoint.md) |  |
|  [getSuggestSearchEndpoint](./shopware-6-client.getsuggestsearchendpoint.md) |  |
|  [handlePaymentEndpoint](./shopware-6-client.handlepaymentendpoint.md) |  |
|  [onConfigChange](./shopware-6-client.onconfigchange.md) |  |
|  [setup](./shopware-6-client.setup.md) | Setup configuration. Merge default values with provided in param. This method will override existing config. For config update invoke \*\*update\*\* method. |
|  [update](./shopware-6-client.update.md) | Update current configuration. This will change only provided values. |


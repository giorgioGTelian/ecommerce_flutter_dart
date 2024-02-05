# food_delivery_ecommerce dart

## project structure

### Home page

Home page displays food category. You can click on it and go to new page to view food and add to the cart. 

### homepage

#### Recommended food page

This page comes from the home page and you can add the item to the cart. The introuduce text about food is collapsible. It also show the product price. And you can add items to the cart.

### Popular food page

This page comes from the home page and you can add the item to the cart. The text about food is collapsible. It also show the product price. And you can add items to your shopping cart.

### Cart page

In this page you place the order. You can also add or remove the items from the cart. As you add or remove you also see the total price changes. This page is dynamic since it removes and add items on user click.

### Sign up page

Sign up using your credential. Once you sign up, the information is submitted to the database and a token for user is generated. This token is used for Authentication.

The commercial license includes phone number verification. Food commercial license registration UI is bit different.

Sign in based on your phone number. The account information is matched on the backend using token and your credential. 

You may sign up using third party service like Twilio or Google provider. Either way, we send a verification code the user and then we login.

### Auth page

If user makes unauthenticated request you, the app takes you to this page. Submitting order to the backend is always checked. Changing user credential is also checked using Authentication.

### History page

You can see this information after you submit order to the backend. From here you will be able(still under development) to monitor your order tracking.

### Local history page

Local history page. It saves in the device itself. You can reorder the item you ordered.

### Update address

You can update your address here. During registration we don't need to put in the address. Address update during check out.

### Pick address

User can pick your address here. This address is dynamic and based on Google map. Google map is a great tool for e-commerce site and delivery products or food.

### Account page

Your personal information is here. Here address could be updated.

### Payment method

We are going to use paypal as a payment method. Soon we will add stripe and other major payment methods.

## payment method for e-commerce

### Paypal login page

Paypal login page. Here we have used paypal web view sdk for loading paypal pages and gateway

### Paypal payment confirm page

Paypal payment confirm page. Here now we are in sandbox mode. Sandbox mode is used for testing.

### Payment success page

After payment has been successful, we redirect to payment successful page. It comes from paypal sdk.


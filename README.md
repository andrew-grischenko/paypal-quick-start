# PayPal Standard Checkout Quick Start

This repo is inspired by the horrible documentation on the PayPal site: [Integrate Standard Checkout](https://developer.paypal.com/docs/checkout/standard/integrate/). It consist of:
* plain html + javascript client
* Node.js + express server

This sample app is built based on the snippets provided on that site and include fixing some bugs and provides the use of the `PayPal-Auth-Assertion` header. 

NOTE: you need to provide your own values from PayPal developers console in the file `.env`: PAYPAL_CLIENT_ID, PAYPAL_CLIENT_SECRET, MERCHANT_ID.

```
npm install
npm start
```


See your transactions log in the [Developers section of PayPal](https://developer.paypal.com/dashboard/dashboard/sandbox)

Feel free to use and enoy :)
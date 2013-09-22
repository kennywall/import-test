---
layout: post
title: "Card Printing API"
url: 'http://kinlane.com/2011/09/05/card-printing-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo/card-sample-image.png'
---

<img src="http://kinlane-productions.s3.amazonaws.com/mimeo/card-sample-image.png" alt="" width="200" align="right" />We've added a new[API that provides card printing services for developers][1]. It enables you to price and order commercially printed cards in different sizes, paper and coating from within your web and mobile applications.

 

These are the different settings currently available for cards:

  * **size**\- 4.25�5.5, 5�7, 5.5�8.5, 6�9
  * **paper**\- White Uncoated 60#, White Uncoated 70#, White Uncoated 70# (100% Recycled), White Glossy 80#, White Glossy 100#
  * **coating**\- None, Glossy Coat (Front Only), Glossy Coat (Front and Back), Protective Coat (Front Only), Protective Coat (Front and Back)

The Card Printing API has five methods currently:

  * [Proof (POST)][2]
  * [Proof (GET)][3]
  * [Quote (GET)][4]
  * [Shipping Options (GET)][5]
  * [Order Quote (GET)][6]
  * [Place Order (POST)][7]
  * [Order Status (GET)][8]

You will also find common error codes, PHP code samples. I will be adding more code samples as they become available.

   [1]: http://mimeoconnect.3scale.net/wiki/card-printing-api (API that provides card printing services for developers)
   [2]: http://mimeoconnect.3scale.net/wiki/card-printing-api#Proof-Post
   [3]: http://mimeoconnect.3scale.net/wiki/card-printing-api#Proof-GET
   [4]: http://mimeoconnect.3scale.net/wiki/card-printing-api#Quote-GET
   [5]: http://mimeoconnect.3scale.net/wiki/card-printing-api#ShippingOptions-GET
   [6]: http://mimeoconnect.3scale.net/wiki/card-printing-api#OrderQuote-GET
   [7]: http://mimeoconnect.3scale.net/wiki/card-printing-api#PlaceOrder-POST
   [8]: http://mimeoconnect.3scale.net/wiki/card-printing-api#OrderStatus-GET

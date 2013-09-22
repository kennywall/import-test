---
layout: post
title: "New Mimeo Poster Printing API"
url: 'http://kinlane.com/2011/08/06/new-mimeo-poster-printing-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-service-providers/mashape-logo.png'
---

[<img src="http://kinlane-productions.s3.amazonaws.com/api-service-providers/mashape-logo.png" alt="" width="200" align="right" />][1]When developers come to[Mimeo Connect][2], they tend to have one thing in mind--printing from their application. The[Mimeo Connect Cloud Print API][3]allows you to print a lot of different type of business documents, but usually developers have a specific type in mind.

Because of this many developers don't have the time to setup their Mimeo.com accounts, and build the documents they are looking to print. They just want to print. To help address this I am playing around some new ways to deliver printing APIs.

Recently I setup a new[Poster Printing API][4]using the[Mashape API platform][1]. Mashape allowed me to quickly add a layer on top of our existing API, that only prints posters. Instead of using Document IDs like the main system, it just takes settings like poster size, paper stock, lamination and mounting.

The new Mimeo Poster Printing API has 5 methods:

<img src="http://kinlane-productions.s3.amazonaws.com/mimeo/posters-sample.png" alt="" align="right" />

  * getOrderQuote
  * getOrderStatus
  * getProof
  * getQuote
  * getShippingOptions
  * placeOrder
  * prepareProof
It provides everything you need to offer poster printing from your application, without the extra steps of setting up a Mimeo.com account, building documents, and using the Mimeo Connect Cloud Print API. But if you want to use the API with your Mimeo Account you can.

The Mashape platform provides very simple documention, an API tester, and code libraries in Java, Ruby, Python, PHP and Obj-C.

The new[Mimeo Poster Printing API][5]is only in alpha. It will place live orders, get live quotes, proofs, etc. But it curently uses a development URL and their is no SSL encrypting transmissions. So use at your own risk.

I'm currently finishing the Mimeo account override and adding options for using against the Mimeo sandbox. I'm looking for some alpha testers who want to use it in their application, let me know if you do not have a Mashape account I can probably get you an invite.

   [1]: http://www.mashape.com/ (Mashape API Platform)
   [2]: http://developer.mimeo.com/ (Mimeo Connect)
   [3]: http://developer.mimeo.com/ (Mimeo Cloud Print API)
   [4]: http://www.mashape.com/apis/Poster%20Printing%20API (Poster Printing API)
   [5]: http://www.mashape.com/apis/Poster%20Printing%20API (Mimeo Poster Printing API)

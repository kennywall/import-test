---
layout: post
title: New Mimeo Poster Printing API
url: http://apievangelist.com/2011/08/06/new-mimeo-poster-printing-api/
source: http://apievangelist.com/2011/08/06/new-mimeo-poster-printing-api/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/api-service-providers/mashape-logo.png
---
{% include JB/setup %}<p>When developers come toMimeo Connect, they tend to have one thing in mind--printing from their application. TheMimeo Connect Cloud Print APIallows you to print a lot of different type of business documents, but usually developers have a specific type in mind.
Because of this many developers don't have the time to setup their Mimeo.com accounts, and build the documents they are looking to print. They just want to print. To help address this I am playing around some new ways to deliver printing APIs.
Recently I setup a newPoster Printing APIusing theMashape API platform. Mashape allowed me to quickly add a layer on top of our existing API, that only prints posters. Instead of using Document IDs like the main system, it just takes settings like poster size, paper stock, lamination and mounting.
The new Mimeo Poster Printing API has 5 methods:


	getOrderQuote
	getOrderStatus
	getProof
	getQuote
	getShippingOptions
	placeOrder
	prepareProof

It provides everything you need to offer poster printing from your application, without the extra steps of setting up a Mimeo.com account, building documents, and using the Mimeo Connect Cloud Print API. But if you want to use the API with your Mimeo Account you can.
The Mashape platform provides very simple documention, an API tester, and code libraries in Java, Ruby, Python, PHP and Obj-C.
The newMimeo Poster Printing APIis only in alpha. It will place live orders, get live quotes, proofs, etc. But it curently uses a development URL and their is no SSL encrypting transmissions. So use at your own risk.
I'm currently finishing the Mimeo account override and adding options for using against the Mimeo sandbox. I'm looking for some alpha testers who want to use it in their application, let me know if you do not have a Mashape account I can probably get you an invite.</p>
<center><p><a href="http://apievangelist.com/2011/08/06/new-mimeo-poster-printing-api/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

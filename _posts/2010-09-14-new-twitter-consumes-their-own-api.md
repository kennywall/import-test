---
layout: post
title: New Twitter Consumes Their Own API
url: http://kinlane.com/2010/09/14/new-twitter-consumes-their-own-api/
image: http://kinlane-productions.s3.amazonaws.com/Twitter-Logo.jpg
---
{% include JB/setup %}

The Twitter mobile site and Twitter Iphone and IPad apps all run using the Twitter API, but now the most popular Twitter client does as well.
This is a very important practice for businesses to adopt. It will put you in the shoes of your developers and API consumers....essentially eating your own dog food.
In 2000 I started a web development company with my wife. I developed a custom content management platform for delivering web sites and applications for my customers. By 2006 I had reached version 3.0 running on Classic ASP and SQL Server 2000, and faced the challenge of migrating to .NET for my Version 4.0. I made the decision to move away from the Microsoft platform and went with PHP and MySQL for my version 4.0.
Over a summer I sat down to develop my Version 4.0. In addition to the language and database change I made another radical decision. I was going to start with the API.
My version 3.0 had 180 separate system I had hand coded, for version 4.0 I chose 75 of the most important and began to develop a set of RESTful web services to drive these systems.
Once I had the database and web services developed I began to create essentially a set of PHP SDK libraries and UI elements that consumed these web services. This became the version 4.0 of my content management system.
I remember several technical folks with partners I had at the time telling me that was the dumbest thing they've heard. APIs aren't for your primary systems? They are for 3rd party integration. I stood by my decision and developed several successful web applications.
Unfortunately I sold my business as part of my divorce with my wife, and when I was packaging up sites to deliver the code to clients I remember several other developers commenting on how strange my decision was. However I did get a couple folks say how interesting it was and were very happy with the architecture I delivered.
Very smart move Twitter, I recommend other companies to do the same with their applications.
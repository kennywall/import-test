---
layout: post
title: "Build vs Buy my Cloud Print API Area"
url: 'http://kinlane.com/2010/11/20/build-vs-buy-my-cloud-print-api-area/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist/3Scale-Logo.jpg'
---

I need to get an API area around my REST Cloud Print API. I have a functional set of RESTful cloud print services, but not much else.

Where do I start? I need a plan. I need to know exactly what it takes to get this API open for business. I built a list of what I need for [phase 1-3 of my API area][1], from the essentials to nice to have.

Now I know what I want...how do I get there? I have the skills to build this myself, and there are also API service providers available that specialize in API delivery. 3Scale, Apigee, and Mashery are three such providers that can help you get your API community up and running. [<img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/3Scale-Logo.jpg" alt="" width="250" align="right" />][2] So I set out on the buy portion of my journey. [3Scale][2], [Apigee][3], and [Mashery][4] deliver a similar set of services, each with a unique approach. They offer extremely robust API delivery platforms, I went through their features and evaluated based upon what was important to me and [Mimeo][5].

I focused on:

  * **API Management** \- All three provide extremely sophisticated mediation of your API and provide policy management, versioning, caching and easy delivery of documentation and code samples. The number of features for managing your API are too many to list.
  * **API Security** \- All three deliver robust security and access control over your API. User, company, and role based access. HTTP Auth and OAuth access to your API, with IP filtering, geo-location features, and protection against SQL injection, DOS attacks and other common vulnerabilities.
  * **API Community** \- All three understand how to take care of your community by delivering the common building blocks like wikis, blogs, and forums. You can deliver a custom branded developer portal and interact and communicate with your API community.
  * **Analytics and Reporting** \- All three deliver comprehensive analytics and reporting. Allowing you to monitor the usage of your API by developer, application, service and method. Give you access to log files and other tools to keep your finger on the pulse of your API.
Even though they have many common features they each had their own unique tools:
  * **Apigee** has a useful API explorer console for assisting developers in discovering, playing with, and debugging against your API. They also deliver in the cloud or on-premise services.
  * **Mashery** provides Salesforce integration, internationalization, log file streaming, and other unique features as well as delivers within the Amazon EC2 cloud.
  * **3Scale** sets themselves apart by offering an API plugin vs. the API proxy methodology of Apigee and Mashery. They also are positioning themselves as the place to start your API with a freemium, pay as you go model.
When it comes to pricing, 3Scale and Apigee are comparable in setup fees and monthly charges. Mashery has a lower setup, but a higher monthly rate than Apigee and 3Scale. [<img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/apigee-logo.jpg" alt="" width="250" align="right" />][3] The cloud pricing varies for each one, with Mashery measuring queries per month, 3Scale measuring transactions per day and Apigee just applying a .0002 per call charge.

At first I didn't feel I had much advice to offer, when helping anyone in my position, trying to decide which API service provider to use. After more consideration, I don't think there is a clear leader here, I think the value is in the process.

Everyone should talk to all three of the [API service providers][6]. They each have their own approach to delivering APIs and their vision of what the future holds. They are all very eager to help you figure things out and get your business.

The process will force you to write down your goals and discuss them with their some very knowledgeable sales and technical teams. Even if you come to the table with a lot of skills, tools, and resources, the process of talking to all three providers will help you understand your situation better. [<img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/Mashery-Logo.gif" alt="" width="250" align="right" />][4] Its clear that 3Scale, Apigee, and Mashery are all still trying to figure this all out just like we are. Its shows in their informal process when discussing your goals, the marketing, pricing and overall flexible approach to solving these problems.

I still haven't decided whether I will build my API area, or buy it from 3Scale, Apigee or Mashery. Although I do understand my position a lot better, and I have read a bunch of case studies, white papers and discussed different approaches.

I'm spending a few days more on my build strategy before I make a decision.

   [1]: http://www.kinlane.com/2010/11/api-ecosystem-strategy/
   [2]: http://www.3scale.net/
   [3]: http://www.apigee.com
   [4]: http://www.mashery.com
   [5]: http://www.mimeo.com
   [6]: http://blog.apievangelist.com/category/services/

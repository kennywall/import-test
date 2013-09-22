---
layout: post
title: "Mimeo Connect Print Marketplace Integrations"
url: 'http://kinlane.com/2011/08/04/mimeo-connect-print-marketplace-integrations/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo/marketplace/Mimeo-Marketplace-Technology.png'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/marketplace/Mimeo-Marketplace-Technology.png" alt="" width="250" align="right" />][1]

One of the most common types of integrations I've been doing lately are [single sign on (SSO) integrations with print marketplaces][2]. On this blog, most of the time I talk about REST API integration with Mimeo, so I wanted to spend some time talking about Mimeo Marketplace integration.

A [Mimeo Marketplace][1] let's you create your own customized online storefront, publish documents, and let others do the ordering ... reducing the time, expense, and resources of pre-printing, storing, and distributing publications yourself. Mimeo prints the documents on-demand and ships them where and when they are needed, even overnight!

There are two primary ways customers can programmatically integrate with their Mimeo Marketplaces:

  * **[Single Sign On (SSO)][3]** \- You can route users from your web site or application directly to a marketplace and immediatley sign them on to their existing user account or create a new Mimeo account for ordering.
  * **[REST API][4]** \- Direct integration with your Mimeo Marketplace via our RESTful API and add, edit, updated and delete product categories and print products within these categories.
Mimeo Marketplaces are free to setup as part of your [Mimeo Account][5], and you can setup both public and private marketplaces.

I've seen some pretty cool print on demand marketplaces setup for everything ranging from learning management system materials to old shakespeare plays for high school. Mimeo Connect allows you to integrate a marketplace directly into your existing web site or application, adding print on demand for all of your content, documents and publications.

I'm going to write more specifically on SSO and integration with [Mimeo Connect][6] using the print marketplace service on our API.

Stay tuned!

   [1]: http://www.mimeo.com/solutions/mimeo-marketplace.php
   [2]: ../../marketplace-sso.php (signle sign on (SSO) integrations with print marketplaces)
   [3]: ../../marketplace-sso.php (Single Sign On)
   [4]: ../../documentation/service_detail.php?ID=2 (REST API)
   [5]: https://my.mimeo.com/Login.aspx?ReturnUrl=/ (Mimeo Account)
   [6]: http://developer.mimeo.com (Mimeo Connect)

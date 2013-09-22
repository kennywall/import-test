---
layout: post
title: "Build Multi-Tenant Apps with Twilio"
url: 'http://kinlane.com/2011/02/02/build-multi-tenant-apps-with-twilio/'
image: 'http://kinlane-productions.s3.amazonaws.com/Twilio.PNG'
---

[Twilio now has subaccounts][1]. You can now build multi-tenant web applications that use the [Twilio Voice or SMS web service][2]s. [<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/Twilio.PNG" alt="" align="right" />][2] Now you can build a single app and create individual "subaccounts" for each customer you have. By segmenting users into subaccounts, you can track the usage of individual customers and provideindividualcustomer billing.

Subaccounts can have their own account sids, phone numbers and caller IDs. You can also access subaccounts calls, SMS, recordings and transcriptions.

Here is the [documentation][3] and [code examples][4] for Twilio subaccounts.

   [1]: http://blog.twilio.com/2011/02/announcing-twilio-subaccounts.html
   [2]: http://www.twilio.com/
   [3]: http://www.twilio.com/docs/api/2010-04-01/rest/subaccounts
   [4]: http://www.twilio.com/docs/howto/subaccounts

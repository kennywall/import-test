---
layout: post
title: "Secure Printing with Google Cloud Print"
url: 'http://kinlane.com/2011/03/13/secure-printing-with-google-cloud-print/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />][1]I've been doing a lot of work with the [Google Cloud Print API][2] lately. I've built a prototype [Google Cloud Print Proxy,][3] and I am trying to push the boundaries of what can be done with Google Cloud Print.

I'm engineering cloud print solutions for commercial printing, and along the way Im also doing a lot of research around device printing.

When it comes to device printing I keep seeing a concept called follow me printing or [pull printing][4]. Where you can queue up a print job from your computer, and then go to printer and print from the device.

Think of this in terms of medical records or other secure documents. You don't want to print down the hall, then have it take 5 minutes to walk there and get it.

With mobile phones, and Google Cloud Printing you can have your document in Google Docs, walk to your target printer, pull out your smart phone and print your document.

You no longer need the device have a pull printing interface. Google Cloud Print and your mobile phone handle securely printing your documents when your ready.

   [1]: http://www.mimeo.com/
   [2]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html (Google Cloud Print API)
   [3]: http://www.kinlane.com/2011/02/google-cloud-print-proxy-cloud-printer/ (Google Cloud Print Proxy)
   [4]: http://en.wikipedia.org/wiki/Pull_printing (Pull printing)

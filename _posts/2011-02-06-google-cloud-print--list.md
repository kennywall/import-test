---
layout: post
title: "Google Cloud Print - List"
url: 'http://kinlane.com/2011/02/06/google-cloud-print-list/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="200" align="right" />][1]In addition to [registering a Google Cloud Printer][2] you may want to list what cloud printers you have registered with a specific Google Account.

After authenticating using [Google ClientLogin API][3], you can request a list of your printers in their account:

The Google Cloud Print /list endpoint accepts the following parameter:

  * **proxy** \- Identification of the proxy, as submitted while registering the printer.

Here is an example JSON response: You can store the list of cloud printers in a database and / or display for the user to navigate and manage their Google Cloud Printers.

######  Related articles

  * [How To Print From Your Phone With Gmail For Mobile ][4]

   [1]: http://www.mimeo.com/
   [2]: http://www.kinlane.com/2011/02/google-cloud-print-register/
   [3]: http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html
   [4]: http://www.makeuseof.com/tag/print-phone-gmail-mobile-google-cloud-print/

---
layout: post
title: "Google Cloud Print Proxy (Cloud Printer)"
url: 'http://kinlane.com/2011/02/08/google-cloud-print-proxy-cloud-printer/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />][1]I have some working code for a [Google Cloud Print Proxy][2]. It is currently written in PHP and uses the [Zend framework][3].

I have written specific blog posts for each service endpoint, and to finish up I wanted to do a complete walk-through.

First I authenticate against a users Google Account with [Google ClientLogin API][4].

Then using the [Google Cloud Print Services Interface][5]:

  * 
I can make calls to the following end points to manage printers:
  * [/register][6]
  * [/list][7]
  * [/update][8]
  * [/delete][9]
I can make calls to the following end points to manage cloud print jobs:
  * [/fetch][10]
  * [/control][11]
You can receive print job notifications via persistent XMPP connection:
  * [XMPP Print Job Notifications][12]
If you want to download the sample code for my Google Cloud Print Proxy work, you can download in the following formats:
  * [git - Github][13]
  * [svn - Google Code][14]
If you have any thoughts or ideas for an innovative Cloud Print Proxy, let me know.

[<img class="c2" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-mimeo.png" alt="" width="500" align="center" />][15]

 

**UPDATE 2/28/2011 -** I have finished the first prototype for the [XMPP print job notification service][16]. This is critical piece to eliminate constant polling of /fetch service.

######  Related articles

  * [Cloud Print "Coming Soon" to Google Docs][17] (readwriteweb.com)
  * [Google sees printing in the cloud][18] (go.theregister.com)
  * [Google Cloud Print is now available][19] (downloadsquad.switched.com)

   [1]: http://mimeo.com/
   [2]: http://www.kinlane.com/2011/02/introduction-to-the-google-cloud-print-services-interface/
   [3]: http://framework.zend.com/
   [4]: http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html
   [5]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html
   [6]: http://www.kinlane.com/2011/02/google-cloud-print-register/
   [7]: http://www.kinlane.com/2011/02/google-cloud-print-list/
   [8]: http://www.kinlane.com/2011/02/google-cloud-print-update/
   [9]: http://www.kinlane.com/2011/02/google-cloud-print-delete/
   [10]: http://www.kinlane.com/2011/02/2822/
   [11]: http://www.kinlane.com/2011/02/google-cloud-print-control/
   [12]: http://www.kinlane.com/2011/02/google-cloud-print-xmpp-print-job-notifications/ (XMPP Print Job Notifications)
   [13]: https://github.com/mimeoconnect/Google-Cloud-Print-Proxy#readme
   [14]: http://code.google.com/p/google-cloud-print-proxy/
   [15]: http://www.mimeo.com/
   [16]: http://www.kinlane.com/2011/02/google-cloud-print-xmpp-print-job-notifications/ (XMPP Print Job Notification Service)
   [17]: http://www.readwriteweb.com/archives/cloud_print_coming_soon_to_google_docs.php
   [18]: http://go.theregister.com/feed/www.theregister.co.uk/2010/12/08/google_cloud_print/
   [19]: http://downloadsquad.switched.com/2010/12/07/google-cloud-print-is-now-available/

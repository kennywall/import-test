---
layout: post
title: "Google Cloud Print"
url: 'http://kinlane.com/2011/03/05/google-cloud-print/'
image: 'http://kinlane-productions.s3.amazonaws.com/google-cloud-print/GCP-Overview.png'
---

[Google Cloud Print][1] provides a printing platform that allow printers to be accessed over the Internet by mobile phone, tables and computers.

Google Cloud Print enables printing over the Internet to web enabled printers or older printers using a proxy software that users can installed on Windows, and soon Mac and Linux platforms.

Cloud Printing is available in Google Apps like Docs and Gmail, Chrome Browser, and the [Google Chrome Operating System.][2] [<img class="aligncenter" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/GCP-Overview.png" alt="" width="550" />][3] Third party software developers can access GCP using an API called the [Google Cloud Print (GCP) Services Interface][4].

The GCP API provides access to the following services for cloud printers:

  * [/register][5]
  * [/list][6]
  * [/update][7]
  * [/delete][8]
The GCP API provides access to each printers print jobs via the following services:
  * [/fetch][9]
  * [/control][10]
Print job notifications are sent to registered printers using a [persistent GTalk / XMPP connection][11].

Google Cloud Print Services provides a platform for managing printers and distributing print jobs to any printer over the Internet.

Using Google Apps and third party software users will be able to print to to home, office and commercial printers on their mobile, table, laptop and desktop computers.

   [1]: http://code.google.com/apis/cloudprint/docs/overview.html (Google Cloud Print)
   [2]: http://www.google.com/chromeos/index.html (Google Chrome OS)
   [3]: http://kinlane-productions.s3.amazonaws.com/google-cloud-print/GCP-Overview.png
   [4]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html (Google Cloud Print Services Interface)
   [5]: http://www.kinlane.com/2011/02/google-cloud-print-register/
   [6]: http://www.kinlane.com/2011/02/google-cloud-print-list/
   [7]: http://www.kinlane.com/2011/02/google-cloud-print-update/
   [8]: http://www.kinlane.com/2011/02/google-cloud-print-delete/
   [9]: http://www.kinlane.com/2011/02/2822/
   [10]: http://www.kinlane.com/2011/02/google-cloud-print-control/
   [11]: http://www.kinlane.com/2011/02/google-cloud-print-xmpp-print-job-notifications/ (Persistent Gtalk / XMPP Connection)

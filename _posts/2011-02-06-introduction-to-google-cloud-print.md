---
layout: post
title: "Introduction to Google Cloud Print"
url: 'http://kinlane.com/2011/02/06/introduction-to-google-cloud-print/'
image: 'http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png'
---

I have been studying [Google][1] [Cloud Print][2] [since they announced it last year][3]. Even though you don't catch me printing very often, I am fascinated by the technology and its potential. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png" alt="" width="300" align="right" /> [Google Cloud Print][4] enables any [application][5] (web, desktop, [mobile][6]) on any device to print to any printer. Applications submit print jobs to the cloud print service via the [API][7] offered by Google.

Google Cloud Print then sends the print job to the selected printer which the user has previously registered with the service. New printers which are called "cloud-aware" and connect directly to the cloud print service, while legacy printers will use a Google Cloud Print Proxy.

Currently [Google provides a proxy that works on Windows with Google Chrome][4]. They will be supporting Mac and Linux versions in the near future.

All of this is fascinating and I see the potential for changing how users interact with their home and office printers, and extend these printers reach on to the mobile web.

However, I'm interested in going further with this. I'm spending time working with the [Google Cloud Print Services API][8] and building a print proxy that can be used in many different situations, beyond interfacing with physical printers.

######  Related articles

  * [Print from Your Phone with Google Cloud Print [Cloud Print]][9] (lifehacker.com)
  * [Print From iOS and Android to Any Printer with Google Cloud Print][10] (wired.com)
  * [Gmail Cloud Print][11] (googlesystem.blogspot.com)

   [1]: http://www.kinlane.com/category/google/
   [2]: http://www.kinlane.com/category/cloud-computing/cloud-print/
   [3]: http://blog.chromium.org/2010/04/new-approach-to-printing.html
   [4]: http://www.google.com/chrome/intl/en/p/cloudprint.html
   [5]: http://www.kinlane.com/category/application/
   [6]: http://www.kinlane.com/category/mobile/
   [7]: http://www.apievangelist.com/
   [8]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html
   [9]: http://lifehacker.com/5742035/heres-how-to-print-from-your-phone-with-google-cloud-print
   [10]: http://www.wired.com/gadgetlab/2011/01/print-from-ios-and-android-to-any-printer-with-google-cloud-print/
   [11]: http://googlesystem.blogspot.com/2011/01/gmail-cloud-print.html

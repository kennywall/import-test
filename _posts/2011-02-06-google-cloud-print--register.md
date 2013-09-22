---
layout: post
title: "Google Cloud Print - Register"
url: 'http://kinlane.com/2011/02/06/google-cloud-print-register/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="200" align="right" />][1]Now that we are [authenticated with a specific users Google Account][2] using the [Google Client Login API][3], we can start registering a cloud printer.

We will register using the GCP /register endpoint:

  * 
Here is our code sample for registering using the Zend framework:

The Google Cloud Print /register endpoint accepts the following parameters:

  * **printer** \- User readable name of the printer being registered (need not be unique).
  * **proxy** \- Identification of the printer client or proxy (must be unique).
  * **capabilities** \- Printer capabilities (XPS or PPD).
  * **defaults** \- Printer default settings (XPS or PPD).
  * **status** \- Status string of the printer�e.g., Out of Paper, Online, etc.
  * **description** \- Descriptive string about the printer.
  * **capsHash** \- A hash or digest value of the capabilities data. This value is useful, for example, to compare values and check whether the local printer's capabilities have changed.

I am using the [PPD format for the printer capabilities][4], in the future I will explore the usage of [XPS][5]. Here is an example JSON response: You now have the cloud printer ID for your registered [Google Cloud Printer][6]. Users can add the printer as a [Google Cloud Printer Proxy][7] and send print jobs to it.

With the printer ID of your new Google Cloud Printer you can manage the printers status, capabilities, and print jobs from users.

######  Related articles

  * [Introduction to the Google Cloud Print Services Interface][8] (kinlane.com)
  * [Google Cloud Print lets you print GMail content from your mobile device][9] (macworld.com)
  * [Google to offer cloud printing for Chrome OS, web apps - predicts "cloud-aware" printers [TNW Google]][10] (thenextweb.com)

   [1]: http://www.mimeo.com/
   [2]: http://www.kinlane.com/2011/02/google-cloud-print-client-login/
   [3]: http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html
   [4]: http://en.wikipedia.org/wiki/PostScript_Printer_Description
   [5]: http://en.wikipedia.org/wiki/Open_XML_Paper_Specification
   [6]: http://www.google.com/chrome/intl/en/p/cloudprint.html
   [7]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html
   [8]: http://www.kinlane.com/2011/02/introduction-to-the-google-cloud-print-services-interface/
   [9]: http://www.macworld.com/article/157364/2011/01/cloudprint.html?lsrc=rss_main
   [10]: http://thenextweb.com/google/2010/11/02/google-to-offer-cloud-printing-for-chrome-os-web-apps-predicts-cloud-aware-printers/

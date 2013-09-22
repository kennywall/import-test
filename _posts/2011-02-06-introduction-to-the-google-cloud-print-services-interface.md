---
layout: post
title: "Introduction to the Google Cloud Print Services Interface"
url: 'http://kinlane.com/2011/02/06/introduction-to-the-google-cloud-print-services-interface/'
image: 'http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png'
---

The [Google Cloud Print services interface][1] or [Google Cloud Print API][1] is where the whole cloud print thing starts getting cool.

The Google Cloud Print service interfaces allow you to create a cloud print proxy that gives you a virtual cloud printer you can send jobs to. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png" alt="" width="300" align="right" /> I'm developing a PHP / MySQL proxy that enables me to register a virtual cloud printer with Google Cloud Print (GCP) registry. Once the printer is registered with the service, it can then receive jobs from and communicate status with Google Cloud Print.

Google defines a **_Cloud Print Proxy_** as: _A cloud print proxy can be a piece of software that runs on a computer connected to a non-cloud-aware printer, a small add-on hardware device that contains the proxy interface and connects to the printer, or firmware that is built in to printers of the future._

I want to evolve the proxy definition beyond just hardware, I want to proxy Google Cloud Print jobs and translate them into anything, but first what is the GCP services interface?

The **URL for the GCP services interface** is:

  * 
Currently GCP services interface uses [Google client login for installed apps][2], although I don't see any reason it can't use [oAuth for Web Apps][3]. Both types of authentication give you access to a users Google Account services, the oAuth for Web Apps is cleaner, and doesn't require you ask for a login.

The Auth token retrieved from authentication will need to be included in all requests using the [HTTP header][4] Authorization: GoogleLogin auth={auth_token}.

In addition, all requests to the Google Cloud Print server will need to incldue the HTTP header: X-CloudPrint-Proxy: {OEM_ID}

Once you are authenticated with a users account you can begin to make calls against the GCP services interface. Google provides the following cloud print endpoints:

  * **[/control][5]** \- Allows proxy control over the status of a cloud print job.
  * **[/delete][6]** \- Allows proxy to delete a printer from Google Cloud Print (GCP) registry.
  * **[/fetch][7]** \- Allows proxy to fetch the next available job for the specified cloud printer.
  * **[/list][8]** \- Provides proxy a listing of all the printers for the given users Google Account.
  * **[/register][9]** \- Allows proxy to register printers.
  * **[/update][10]** \- Allows proxy to update various attributes and parameters of the printer registered with Google Cloud Print.
The GCP services interface gives you access to everything you for managing Google Cloud printers and jobs. Google Cloud Print can also provide print job availability notification through Google Talk, using a persistent [XMPP][11] connection. [<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />][12] I have a working XMPP script, because my focus goes beyond instant gratification from a local printer, into more a commercial cloud print format, I'm not implementing the XMPP jobs management and just relying on the /fetch and /control endpoints to manage jobs.

That concludes a quick overview of the GCP services interface, I will be publishing specific Google Cloud Print code samples for each step shortly. You can also find [a Google Cloud Print Developers][13] [Guide and Google Cloud Print Services Interface Guide][1] over at Google Code.

######  Related articles

  * [Cloud Print "Coming Soon" to Google Docs][14] (readwriteweb.com)
  * [Wireless Printing From Gmail Coming Soon to Android and iOS][15] (mashable.com)
  * [Google Cloud Print lets you print GMail content from your mobile device][16] (macworld.com)

   [1]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html
   [2]: http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html
   [3]: http://code.google.com/apis/accounts/docs/OAuth.html
   [4]: http://en.wikipedia.org/wiki/List_of_HTTP_header_fields (List of HTTP header fields)
   [5]: http://www.kinlane.com/2011/02/google-cloud-print-control/
   [6]: http://www.kinlane.com/2011/02/google-cloud-print-delete/
   [7]: http://www.kinlane.com/2011/02/2822/
   [8]: http://www.kinlane.com/2011/02/google-cloud-print-list/
   [9]: http://www.kinlane.com/2011/02/google-cloud-print-register/
   [10]: http://www.kinlane.com/2011/02/google-cloud-print-update/
   [11]: http://en.wikipedia.org/wiki/Extensible_Messaging_and_Presence_Protocol (Extensible Messaging and Presence Protocol)
   [12]: http://www.mimeo.com
   [13]: http://code.google.com/apis/cloudprint/docs/devguide.html
   [14]: http://www.readwriteweb.com/archives/cloud_print_coming_soon_to_google_docs.php
   [15]: http://mashable.com/2011/01/24/google-cloud-print-gmail-mobile/
   [16]: http://www.macworld.com/article/157364/2011/01/cloudprint.html?lsrc=rss_main

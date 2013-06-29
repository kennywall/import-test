---
layout: post
title: Google Cloud Print Proxy Cloud Printer
url: http://kinlane.com/2011/02/08/google-cloud-print-proxy-cloud-printer/
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}
<p>
     I have some working code for a Google Cloud Print Proxy. It is currently written in PHP and uses the Zend framework. I have written specific blog posts for each service endpoint, and to finish up I wanted to do a complete walk-through. First I authenticate against a users Google Account with Google ClientLogin API. Then using the Google Cloud Print Services Interface: http://www.google.com/cloudprint/interface/ I can make calls to the following end points to manage printers: /register /list /update /delete I can make calls to the following end points to manage cloud print jobs: /fetch /control You can receive print job notifications via persistent XMPP connection: XMPP Print Job Notifications If you want to download the sample code for my Google Cloud Print Proxy work, you can download in the following formats: git - Github svn - Google Code If you have any thoughts or ideas for an innovative Cloud Print Proxy, let me know.   UPDATE 2/28/2011 - I have finished the first prototype for the XMPP print job notification service. This is critical piece to eliminate constant polling of /fetch service. Related articles Cloud Print "Coming Soon" to Google Docs (readwriteweb.com) Google sees printing in the cloud (go.theregister.com) Google Cloud Print is now available (downloadsquad.switched.com)
</p>
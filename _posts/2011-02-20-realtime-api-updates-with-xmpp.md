---
layout: post
title: "Real-Time API Updates with XMPP"
url: 'http://kinlane.com/2011/02/20/real-time-api-updates-with-xmpp/'
image: 'http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png'
---

[<img src="http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png" alt="" align="right" />][1]I'm working on my prototype for a [Google][2] cloud printer that runs on a server.

To set the stage, I want to get cloud print jobs sent from [Google Docs][3] using the [Google Cloud Print Services Interface][4].

You can retrieve a print job from the Google Cloud Print Services interface using /fetch.

All it takes to get a new job is making a call to the Google Cloud Print (GCP) [API][5] on a regular schedule.

The problem with this method is that it isn't real-time, is it? Even if you poll the GCP API every minute...it isn't real-time.

To make it real time Google uses a separate [XMPP][6] connection for sending print notifications to cloud printers.

Each cloud printer has to register with the service and get a ClientLogin token, then establish a perseistent connection with the GTalk server to receive updates.

With a cloud printer authenticated, and a persisistent [XMPP][1] connection established a cloud print server can then wait for print job notifications.

Two benefits from this method:<img src="http://kinlane-productions.s3.amazonaws.com/real-time.jpg" alt="" width="200" align="right" />

  1. **Real-Time -** XMPP makes the GCP API requests truly real-time. As the print job comes in, an XMPP message is sent outnotifyingthe cloud printer.
  2. **Resources -** This is a much more efficient usage of network and compute resources. Cloud Printers only poll the GCP API /fetch end point when it receives job update.
As I'm working with the GCP API and building the XMPP notification system I start thinking about this outside of print and the Google Cloud Print API.

XMPP notifications is a great way to make APIs truly real-time, as well as reduce the request load on an API. It reduces the need to constantly poll an API for updates.

Think if [Twitter][7] provided [XMPP][8] updates for applications looking for search updates. They would getnotifiedto make an API request when there is truly an update.

######  Related articles

  * [Printing with Google Cloud Print and XMPP][9] (kinlane.com)
  * [Email, XMPP, and Task Queues in Google AppEngine][10] (oreilly.com)
  * [Google Cloud Print - Fetch][11] (kinlane.com)

   [1]: http://xmpp.org/
   [2]: http://www.kinlane.com/category/google/
   [3]: http://www.kinlane.com/category/google/google-docs/
   [4]: http://code.google.com/apis/cloudprint/docs/overview.html
   [5]: http://www.apievangelist.com/
   [6]: http://en.wikipedia.org/wiki/Extensible_Messaging_and_Presence_Protocol (Extensible Messaging and Presence Protocol)
   [7]: http://www.kinlane.com/category/twitter/
   [8]: http://www.kinlane.com/category/xmpp/
   [9]: http://www.kinlane.com/2011/01/printing-with-google-cloud-print-and-xmpp/
   [10]: http://oreilly.com/catalog/0636920010845/
   [11]: http://www.kinlane.com/2011/02/2822/

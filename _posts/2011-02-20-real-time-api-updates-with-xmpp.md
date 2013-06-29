---
layout: post
title: Real Time API Updates with XMPP
url: http://kinlane.com/2011/02/20/real-time-api-updates-with-xmpp/
image: http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png
---
{% include JB/setup %}
I'm working on my prototype for a Google cloud printer that runs on a server.
To set the stage, I want to get cloud print jobs sent from Google Docs using the Google Cloud Print Services Interface.
You can retrieve a print job from the Google Cloud Print Services interface using /fetch.
All it takes to get a new job is making a call to the Google Cloud Print (GCP) API on a regular schedule.
The problem with this method is that it isn't real-time, is it? Even if you poll the GCP API every minute...it isn't real-time.
To make it real time Google uses a separate XMPP connection for sending print notifications to cloud printers.
Each cloud printer has to register with the service and get a ClientLogin token, then establish a perseistent connection with the GTalk server to receive updates.
With a cloud printer authenticated, and a persisistent XMPP connection established a cloud print server can then wait for print job notifications.
Two benefits from this method:

	Real-Time - XMPP makes the GCP API requests truly real-time. As the print job comes in, an XMPP message is sent outnotifyingthe cloud printer.
	Resources - This is a much more efficient usage of network and compute resources. Cloud Printers only poll the GCP API /fetch end point when it receives job update.

As I'm working with the GCP API and building the XMPP notification system I start thinking about this outside of print and the Google Cloud Print API.
XMPP notifications is a great way to make APIs truly real-time, as well as reduce the request load on an API. It reduces the need to constantly poll an API for updates.
Think if Twitter provided XMPP updates for applications looking for search updates. They would getnotifiedto make an API request when there is truly an update.
Related articles

	Printing with Google Cloud Print and XMPP (kinlane.com)
	Email, XMPP, and Task Queues in Google AppEngine (oreilly.com)
	Google Cloud Print - Fetch (kinlane.com)


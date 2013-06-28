---
layout: post
title: Google Has a Solid Vision of Cloud Printing
url: http://apievangelist.com/2011/03/31/googles-vision-of-the-future-of-cloud-printing/
source: http://apievangelist.com/2011/03/31/googles-vision-of-the-future-of-cloud-printing/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png
---
{% include JB/setup %}<p>Google is moving forward with their vision of Cloud Printing in a much larger, comprehensive and decisive way compared with HP ePrint or Apple Airprint.
They have rolled out the Google Cloud Print Services Interface as well as an XMPP jobs notification system.
GCP supports printing on mobile phones using Google Docs and Gmail, while also supporting printing in Chrome on Windows, and now on the Mac Platform.
They quickly evolved from a Google Client Login to support OAuth 2.0, to keep in line with the rest of the Google API ecosystem when it comes to authentication.
They also have a clear stance on an architecture where the printers connect directly to cloud print services versus one where the GCP service connects to your printers via a proxy.
Google is strongly recommending that developers and device manufacturers allow users to connect their printers directly to the cloud services and bypass a proxy. Their reasoning for this is:

	Simplicity - Fewer moving parts means easier development and fewer maintenance problems.
	Privacy - Users are concerned with putting their data in the cloud, and routing through a proxy adds another layer to be concerned about.
	Development Speed - Developing, scaling, and managing a cloud based print service is costly and time consuming. Enabling printers to work directly with GCP, eliminates a lot of development effort.

Many developers are building proxies to offer analytics, operation management, secure printing, green print management and many other features.
This can be done without forcing printers to route through a proxy.   If manufacturers build printers to be web-enabled, they can work directly with GCP services.   Then operational and management systems can access users accounts using the GCP services interface.

This just makes sense.   I get a lot of questions via email, twitter and comments on my site regarding how to diagnose printer problems using Google Cloud Print.
The biggest question I get is how users can print when their computers are offline.   I think this is the most obvious aspect that Google is trying to point out with their vision.   If devices are web-enabled and work directly with GCP, it eliminates the need to leave computers on and introducing another point where problems can occur.
The goal of Google Cloud Print is empower the user with easy, hassle free printing to any device.</p>
<center><p><a href="http://apievangelist.com/2011/03/31/googles-vision-of-the-future-of-cloud-printing/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

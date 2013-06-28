---
layout: post
title: Google Cloud Print, HP ePrint, and Apple Airprint
url: http://apievangelist.com/2011/03/05/google-cloud-print-hp-eprint-and-apple-airprint/
source: http://apievangelist.com/2011/03/05/google-cloud-print-hp-eprint-and-apple-airprint/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/apple-airprint/ipad-and-airprint.jpg
---
{% include JB/setup %}<p>I've been spending time learning about the three major platform we think about when we hear the term cloud printing.

	Apple Airprint
	HP ePrint
	Google Cloud Print

As I'm learning about the details of each printing platform, I can't help but compare them against each other. Here are some things I'm tracking on:
Apple Airprint provides printing on IOS and Mac platforms over a local network to HP web connected printers.

HP ePrint provides printing over the Internet to any HP web connected printer.  Each printer registers itself with the HP ePrint Center and gets assigned an email address.    Print jobs are delivered via email to each printer.
Google Cloud Print provides printing over the Internet to any local, office or commercial printer.
Apple isn't quite in the same league as HP and Google Cloud Print.   Airprint only provides local network printing.  HP provides a cloud system dedicated to their HP web connected printers, while Google is building a cloud system that is accessible by any printer.
Airprint is integrated into the IOS and Mac OS, and Google Cloud Print is integrated into Google Apps and the Google Chrome OS.    HP doesn't have this type of integration exposure.
Google Cloud Print provides custom application development using Google Apps and provides document resources through Google Docs Template Gallery.
HP ePrint provides a custom application platform for their printers, and home and business document resources through their Marketsplash, and Creative Studio for home and business.

HP uses email to register and route print jobs to printers over the Internet.
Google uses an API to register printers and fetch print jobs, then uses GTalk, which employs XMPP, a messaging and presence protocol used to route print job notifications.
I'm not sure what Apple uses to route register printers and route print jobs yet.
Its an interesting mix of cloud printing technology, and perspectives on what cloud printing is:
Apple has IPhone, IPad, but Airprint can only print locally at the current time.

HP ePrint can only print to HP printers, but is available anywhere over the Internet.  HP is also developing integration with Google Cloud Print, and also Apple Airprint can only print to HP web connected printers.
Google has the Android platform, Google Apps and Google Chrome OS.  Google also is accessible on the IPhone and IPad as well as having an application on the HP ePrint platform. Google provides support for any printer, new or old as well provides access to commercial printers.
Currently Google seems to have the lead with a much wider platform and accessibility.  Although there is no questioning Apples dominance in the mobile market, and HP in the printer market.
It will be an interesting year to see where these cloud print players go with their platforms.
</p>
<center><p><a href="http://apievangelist.com/2011/03/05/google-cloud-print-hp-eprint-and-apple-airprint/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

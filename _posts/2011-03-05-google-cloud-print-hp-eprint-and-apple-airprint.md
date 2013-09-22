---
layout: post
title: "Google Cloud Print, HP ePrint, and Apple Airprint"
url: 'http://kinlane.com/2011/03/05/google-cloud-print-hp-eprint-and-apple-airprint/'
image: 'http://kinlane-productions.s3.amazonaws.com/apple-airprint/ipad-and-airprint.jpg'
---

I've been spending time learning about the three major platform we think about when we hear the term **_cloud printing_**.

  * [Apple Airprint][1]
  * [HP ePrint][2]
  * [Google Cloud Print][3]
As I'm learning about the details of each printing platform, I can't help but compare them against each other. Here are some things I'm tracking on:

_[Apple Airprint][4] provides printing on IOS and Mac platforms over a local network to HP web connected printers._ <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/apple-airprint/ipad-and-airprint.jpg" alt="" width="300" align="right" />

_[HP ePrint][5] provides printing over the Internet to any HP web connected printer. Each printer registers itself with the HP ePrint Center and gets assigned an email address. Print jobs are delivered via email to each printer._

_[Google Cloud Print][6] provides printing over the Internet to any local, office or commercial printer._

_Apple isn't quite in the same league as HP and Google Cloud Print. Airprint only provides local network printing. HP provides a cloud system dedicated to their HP web connected printers, while Google is building a cloud system that is accessible by any printer._

_Airprint is integrated into the IOS and Mac OS, and Google Cloud Print is integrated into Google Apps and the Google Chrome OS. HP doesn't have this type of integration exposure._

_Google Cloud Print provides custom application development using Google Apps and provides document resources through Google Docs Template Gallery._

_HP ePrint provides a custom application platform for their printers, and home and business document resources through their Marketsplash, and Creative Studio for home and business._ <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/HP-ePrint/hp_eprint_center.jpg" alt="" width="200" align="right" />

_HP uses email to register and route print jobs to printers over the Internet._

_Google uses an API to register printers and fetch print jobs, then uses [GTalk][7], which employs XMPP, a messaging and presence protocol used to route print job notifications._

_I'm not sure what Apple uses to route register printers and route print jobs yet._ Its an interesting mix of cloud printing technology, and perspectives on what cloud printing is:

_Apple has IPhone, IPad, but Airprint can only print locally at the current time._ <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png" alt="" width="250" align="right" />

_HP ePrint can only print to HP printers, but is available anywhere over the Internet. HP is also developing integration with Google Cloud Print, and also Apple Airprint can only print to HP web connected printers._

_Google has the Android platform, Google Apps and Google Chrome OS. Google also is accessible on the IPhone and IPad as well as having an application on the HP ePrint platform. Google provides support for any printer, new or old as well provides access to commercial printers._ Currently Google seems to have the lead with a much wider platform and accessibility. Although there is no questioning Apples dominance in the mobile market, and HP in the printer market.

It will be an interesting year to see where these cloud print players go with their platforms.

   [1]: http://www.kinlane.com/2011/03/apple-airprint/ (Apple Airprint)
   [2]: http://www.kinlane.com/2011/03/hp-eprint-web-connected-printers/ (HP ePrint)
   [3]: http://www.kinlane.com/2011/03/google-cloud-print/ (Google Cloud Print)
   [4]: http://support.apple.com/kb/ht4356 (Apple Airprint)
   [5]: http://h30495.www3.hp.com/about/eprint (HP ePrint)
   [6]: http://code.google.com/apis/cloudprint/docs/overview.html (Google Cloud Print)
   [7]: http://www.google.com/talk/ (Google Talk)

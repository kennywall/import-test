---
layout: post
title: "Printing with Google Cloud Print and XMPP"
url: 'http://kinlane.com/2011/01/27/printing-with-google-cloud-print-and-xmpp/'
image: 'http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png'
---

The potential of decentralized technologies on the Internet is far greater than their counterparts. One such technology is [XMPP][1], Extensible Messaging and Presence Protocol or XMPP, is an open technology for real-time communication, which you find in instant messaging, multi-party chat, voice and video calls, collaboration, and content syndication applications. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png" alt="" align="right" /> I am diving into the protocol while building commercial print applications that utilize the [Google Cloud Print][2] protocol. Using the [Google Cloud Print Services API][3] I can register commercial print applications as cloud printers on the Google Clound Print network.

Once I register a commercial cloud print on the network, then authenticate with a user using [Google authentication and authorization APIs][4] the printer is ready for printing. Print jobs availability is then handled through [Google Talk][5], using a persistent XMPP connection.

I'm refreshing my memory on the [XMPP standard][1] as well as researching four PHP XMPP classes:

  * [Loudmouth][6]
  * [jaxl][7]
  * [xmpphp][8]
  * [Eiffel XMPP][9]
Although XMPP has its roots in communication its fascinatng to see the innovation around it into other areas of real-time programming such as [cloud printing][10].

Even though the core technology is stable, the XMPP community continues to define various XMPP extensions, ther is also an active community of open-source and commercial developers further pushing the boundaries of whats possible with XMPP.

   [1]: http://xmpp.org/
   [2]: http://code.google.com/apis/cloudprint/
   [3]: http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html
   [4]: http://code.google.com/apis/accounts/docs/OAuth.html
   [5]: http://www.google.com/talk/
   [6]: http://groups.google.com/group/loudmouth-dev?pli=1
   [7]: http://code.google.com/p/jaxl/
   [8]: http://code.google.com/p/xmpphp/
   [9]: http://bricabrac.origo.ethz.ch/wiki/Eiffel_XMPP
   [10]: http://www.kinlane.com/category/cloud-computing/cloud-print/

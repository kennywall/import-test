---
layout: post
title: Printing with Google Cloud Print and XMPP
url: http://apievangelist.com/2011/01/27/printing-with-google-cloud-print-and-xmpp/
source: http://apievangelist.com/2011/01/27/printing-with-google-cloud-print-and-xmpp/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png
---
{% include JB/setup %}The potential of decentralized technologies on the Internet is far greater than their counterparts.  One such technology is XMPP,  Extensible Messaging and Presence Protocol or XMPP, is an open technology for real-time communication, which you find in instant messaging, multi-party chat, voice and video calls, collaboration, and content syndication applications.

I am diving into the protocol while building commercial print applications that utilize the Google Cloud Print protocol.    Using the Google Cloud Print Services API I can register commercial print applications as cloud printers on the Google Clound Print network.
Once I register a commercial cloud print on the network, then authenticate with a user using Google authentication and authorization APIs the printer is ready for printing.  Print jobs availability is  then handled through Google Talk, using a persistent XMPP connection.
I'm refreshing my memory on the XMPP standard as well as researching four PHP XMPP classes:

	Loudmouth
	jaxl
	xmpphp
	Eiffel XMPP

Although XMPP has its roots in communication its fascinatng to see the innovation around it into other areas of real-time programming such as cloud printing.
Even though the core technology is stable, the XMPP community continues to define various XMPP extensions, ther is also an active community of open-source and commercial developers further pushing the boundaries of whats possible with XMPP.
---
layout: post
title: "Google Cloud Print Job Notifications Using XMPP"
url: 'http://kinlane.com/2011/02/28/google-cloud-print-xmpp-print-job-notifications/'
image: 'http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-mimeo.png'
---

<img src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-mimeo.png" alt="" width="350" align="right" />I made it over the last hurdle building my [Google Cloud Print Proxy][1] in PHP.

I have a prototype for the Google Cloud Print, XMPP Print Job Notification Service.

Even though you can pull print jobs via the GCP /fetch interface, Google requires cloud print proxies to receive print job notifications via an XMPP push, rather than constantly polling the /fetch interface.

It make sense. Using XMPP is a great way to receive API notifications, and minimize requests to an API. Companies like Superfeedr are using[PubSubHubbub for API notifications][2].

I am building on top the [XMPPHP library][3] for my Google Cloud Print XMPP Service.

First I authenticate with the Google Talk Service using Client Login and ChromiumSync Service.

Then I setup a persistent XMPP connection with the Google Talk Service on behalf of my Google Cloud Print user, for my Printer Proxy.

When you establish [persistent connection][4] with Google Talk Service using XMPP it will return a Full [JID][5] and Bare JID for your persistent XMPP connection.

Once the session begins you send the following subscription stanza:

The service will acknowledge your subscription by returning the following:

Once subscribed, my persistent XMPP will handle and process any messages from cloudprint.google.com notifying of new cloud print jobs for users.

<img class="c2" src="http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png" alt="" width="150" align="right" /> I still have a lot of work to do to make the Google Cloud Print Proxy handle jobs flawlessly.

I need to setup the XMPP print jobs notifications to handle print jobs for all users that have a print proxy registered.

The XMPP print job notification service has to be running 24 / 7 and initiate the print job /fetch via API, and the commercial print process for each job.

Once I get this cleaned up a little more I will publish a PHP class for working with Google Cloud Print Services Interface and XMPP Print Job Notifications to Github.

   [1]: http://www.kinlane.com/2011/02/google-cloud-print-proxy-cloud-printer/ (Google Cloud Print Proxy)
   [2]: http://blog.apievangelist.com/2011/02/23/pubsubhubbub-for-apis/ (PubSubHubbub for API Notifications)
   [3]: http://code.google.com/p/xmpphp/ (XMPHP Library)
   [4]: http://en.wikipedia.org/wiki/HTTP_persistent_connection (HTTP persistent connection)
   [5]: http://en.wikipedia.org/wiki/Extensible_Messaging_and_Presence_Protocol (Extensible Messaging and Presence Protocol)

---
layout: post
title: "Mobile Data Gathering"
url: 'http://kinlane.com/2009/12/15/mobile-data-gathering/'
image: ''
---

While playing around with Google Fusion Tables tonight I came across the [Open Data Kit][1] (ODK).

Open Data Kit (ODK) is a suite of tools to help organizations collect, aggregate and visualize their data. The project's goals are to make open-source and standards-based tools which are easy to try, easy to use, easy to modify and easy to scale.

The project consists of:

  * [ODK Collect][2] \- ODK Collect is powerful phone based replacement for your paper forms. Collect is built on the [Android][3]
  * [ODK Aggregate][4] \- ODK Aggregate provides a ready to deploy online repository to store, view and export collected data. Aggregate is currently implemented on [Google App Engine][5] and enables free hosting of data on Google's reliable infrastructure.
  * [ODK Manage][6] \- ODK Manage maintains a [database][7] of all phones in a deployment to enable remote [device management][8]. By sending an [SMS][9] to a deployed phone, Manage can trigger the transfers of forms, data, and applications.
  * [ODK Validate][10] \- ODK Validate ensures that you have a [OpenRosa][11] complaint form -- one that will also work with all the ODK tools.
  * [ODK Voice][12] \- ODK Voice facilities mapping [XForms][13] to sound snippets that can be played over a "robo" call to any phone. Responses are collected using the phone's keypad ([DTMF][14]) and are automatically aggregated.
Cool stuff!

Great way to build mobile survey and data gathering applications that can be easily downloaded onto mobile phones such as Google Android.

   [1]: http://code.google.com/p/open-data-kit/
   [2]: http://code.google.com/p/open-data-kit/wiki/ODKCollect
   [3]: http://www.android.com/
   [4]: http://code.google.com/p/open-data-kit/wiki/ODKAggregate
   [5]: http://code.google.com/appengine/docs/whatisgoogleappengine.html
   [6]: http://code.google.com/p/open-data-kit/wiki/ODKManage
   [7]: http://en.wikipedia.org/wiki/Database (Database)
   [8]: http://en.wikipedia.org/wiki/Device_Management (Device Management)
   [9]: http://en.wikipedia.org/wiki/SMS (SMS)
   [10]: http://code.google.com/p/open-data-kit/wiki/ODKValidate
   [11]: http://code.javarosa.org/
   [12]: http://code.google.com/p/open-data-kit/wiki/ODKVoice
   [13]: http://en.wikipedia.org/wiki/XForms (XForms)
   [14]: http://en.wikipedia.org/wiki/Dual-tone_multi-frequency (Dual-tone multi-frequency)

---
layout: post
title: "Google Releases Two New APIs for Chrome Extensions"
url: 'http://kinlane.com/2011/04/04/google-releases-two-new-apis-for-chrome-extensions/'
image: 'http://kinlane-productions.s3.amazonaws.com/google-chrome-logo.jpg'
---

<img src="http://kinlane-productions.s3.amazonaws.com/google-chrome-logo.jpg" alt="" width="250" align="right" />In the latest Chrome Beta release, Google made available [two new experimental extension APIs][1]: the Web Navigation and Proxy Extension APIs.

  * [Web Navigation Extension API][2] \- Allows extension developers to observe browser navigation events. The API therefore allows an extension to keep track of exactly what page the tab is showing, and how the user got there.
  * [Proxy Extension API][3] \- Allows users to configure Chrome's proxy settings via extensions. Proxies can be configured for the entire browser or independently for regular and incognito windows.
You can test drive these new APIs by enabling Experimental Extension APIs.

Until the APIs are stable, they require explicit permission from users.

   [1]: http://blog.chromium.org/2011/04/new-experimental-apis-for-chrome.html (two new experimental extension APIs)
   [2]: http://code.google.com/chrome/extensions/trunk/experimental.webNavigation.html (Web Navigation Extension API)
   [3]: http://code.google.com/chrome/extensions/trunk/experimental.proxy.html (Proxy Extension API)

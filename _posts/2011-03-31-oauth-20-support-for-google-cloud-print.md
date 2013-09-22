---
layout: post
title: "OAuth 2.0 Support for Google Cloud Print"
url: 'http://kinlane.com/2011/03/31/oauth-2-0-support-for-google-cloud-print/'
image: 'http://kinlane-productions.s3.amazonaws.com/OAuth2.png'
---

<img src="http://kinlane-productions.s3.amazonaws.com/OAuth2.png" alt="" width="200" align="right" />Up until now Google Cloud Print has only support the [Google Client Login][1].

Google Cloud Print now supports [OAuth 2.0][2].

The XMPP print job notification system does not yet recognize the OAuth token, but will shortly.

For now users can just use /fetch polling as long as its minimal, and resume using XMPP for print jobs notification when its ready.

To make an XMPP connection with OAuth2 developers will need to change

   [1]: http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html (Coogle Client Login)
   [2]: http://wiki.oauth.net/w/page/25236487/OAuth-2 (OAuth 2.0)

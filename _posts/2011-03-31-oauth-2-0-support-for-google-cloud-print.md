---
layout: post
title: OAuth 2.0 Support for Google Cloud Print
url: http://kinlane.com/2011/03/31/oauth-2-0-support-for-google-cloud-print/
source: http://kinlane.com/2011/03/31/oauth-2-0-support-for-google-cloud-print/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/OAuth2.png
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <img src="http://kinlane-productions.s3.amazonaws.com/OAuth2.png" alt="" width="200" align="right" />Up until now Google Cloud Print has only support the <a title="Coogle Client Login" href=
    "http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html">Google Client Login</a>. Google Cloud Print now supports <a title="OAuth 2.0" href=
    "http://wiki.oauth.net/w/page/25236487/OAuth-2">OAuth 2.0</a>. The XMPP print job notification system does not yet recognize the OAuth token, but will shortly. For now users can just use /fetch
    polling as long as its minimal, and resume using XMPP for print jobs notification when its ready. To make an XMPP connection with OAuth2 developers will need to change &lt;X-Google-Token&gt; to
    &lt;X-Oauth2&gt; and rename the channel from "cloudprint.google.com/&lt;PRINTER_ID&gt;" to "cloudprint.google.com"
  </body>
</html></p>

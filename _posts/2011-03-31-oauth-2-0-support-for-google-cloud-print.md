---
layout: post
title: OAuth 2 0 Support for Google Cloud Print
url: http://kinlane.com/2011/03/31/oauth-2-0-support-for-google-cloud-print/
image: http://kinlane-productions.s3.amazonaws.com/OAuth2.png
---
{% include JB/setup %}
<p>
     Up until now Google Cloud Print has only support the Google Client Login. Google Cloud Print now supports OAuth 2.0. The XMPP print job notification system does not yet recognize the OAuth token, but will shortly. For now users can just use /fetch polling as long as its minimal, and resume using XMPP for print jobs notification when its ready. To make an XMPP connection with OAuth2 developers will need to change &lt;X-Google-Token&gt; to &lt;X-Oauth2&gt; and rename the channel from "cloudprint.google.com/&lt;PRINTER_ID&gt;" to "cloudprint.google.com"
</p>
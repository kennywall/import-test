---
layout: post
title: Google Cloud Print Job Notifications Using XMPP
url: http://apievangelist.com/2011/02/28/google-cloud-print-xmpp-print-job-notifications/
source: http://apievangelist.com/2011/02/28/google-cloud-print-xmpp-print-job-notifications/
domain: apievangelist.com
image: [Image]
---
{% include JB/setup %}<p>I made it over the last hurdle building my Google Cloud Print Proxy in PHP.I have a prototype for the Google Cloud Print, XMPP Print Job Notification Service.Even though you can pull print jobs via the GCP /fetch interface, Google requires cloud print proxies to receive print job notifications via an XMPP push, rather than constantly polling the /fetch interface.It make sense.Using XMPP is a great way to receive API notifications, and minimize requests to an API.</p>
<center><p><a href="http://apievangelist.com/2011/02/28/google-cloud-print-xmpp-print-job-notifications/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

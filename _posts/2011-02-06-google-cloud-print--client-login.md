---
layout: post
title: Google Cloud Print - Client Login
url: http://apievangelist.com/2011/02/06/google-cloud-print-client-login/
source: http://apievangelist.com/2011/02/06/google-cloud-print-client-login/
domain: apievangelist.com
image: [Image]
---
{% include JB/setup %}<p>Now lets start using Google Cloud Print API.First thing is we need to do, is authenticate with our  targeted users Google Account using the Client Login API.The easiest way to work with Google APIs in PHP, is to use the Zend framework.With just a couple lines of code we can authenticate with any users Google Account:

The ClientLogin API requires you to use the users Google Account email and password and using Zend we can create a $client object  for the users account.Using the getClientLoginToken() method we can get the Auth Token we will need to make each API call.</p>
<center><p><a href="http://apievangelist.com/2011/02/06/google-cloud-print-client-login/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

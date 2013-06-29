---
layout: post
title: Google Cloud Print Client Login
url: http://kinlane.com/2011/02/06/google-cloud-print-client-login/
image: https://gist.github.com/813841.js?file=Google%20Cloud%20Print%20Services%20Interface%20-%20Client%20Login
---
{% include JB/setup %}

The easiest way to work with Google APIs in PHP, is to use the Zend framework.
With just a couple lines of code we can authenticate with any users Google Account:

The ClientLogin API requires you to use the users Google Account email and password and using Zend we can create a $client object  for the users account.

Using the getClientLoginToken() method we can get the Auth Token we will need to make each API call.
The tokens returned by ClientLogin expire every 28 days and require re-authentication.
This example only authenticates against the Google Cloud Print Service Interface, to receive job notifications using the Talk service  you will need to change the service to be �chromiumsync �.
Now you should be successfully authenticated with the users account and can start making calls against the Google Cloud Print Service Interface.
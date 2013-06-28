---
layout: post
title: Google Cloud Print - Client Login
url: http://kinlane.com/2011/02/06/google-cloud-print-client-login/
source: http://kinlane.com/2011/02/06/google-cloud-print-client-login/
domain: kinlane.com
image: https://gist.github.com/813841.js?file=Google%20Cloud%20Print%20Services%20Interface%20-%20Client%20Login
---
{% include JB/setup %}

<p>
     Now lets start using <a href="http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html" target="_blank">Google Cloud Print API</a>. First thing is we need to do, is authenticate with our targeted users Google Account using the C<a href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html" target="_blank">lient Login API</a>. The easiest way to work with Google APIs in PHP, is to use the <a href="http://framework.zend.com/" target="_blank">Zend framework</a>. With just a couple lines of code we can authenticate with any users Google Account:
</p><script src="https://gist.github.com/813841.js?file=Google%20Cloud%20Print%20Services%20Interface%20-%20Client%20Login" type="text/javascript">
</script>
<p>
     The ClientLogin API requires you to use the users Google Account email and password and using Zend we can create a $client object for the users account. <a href="http://www.mimeo.com" target="_blank"><img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="200" align="right" /></a> Using the getClientLoginToken() method we can get the Auth Token we will need to make each API call. The tokens returned by ClientLogin expire every 28 days and require re-authentication. This example only authenticates against the Google Cloud Print Service Interface, to receive job notifications using the Talk service you will need to change the service to be �chromiumsync �. Now you should be successfully authenticated with the users account and can start making calls against the <a href="http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html" target="_blank">Google Cloud Print Service Interface</a>.
</p>
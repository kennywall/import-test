---
layout: post
title: Google Cloud Print - Register
url: http://apievangelist.com/2011/02/06/google-cloud-print-register/
source: http://apievangelist.com/2011/02/06/google-cloud-print-register/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}<p>Now that we are authenticated with a specific users Google Account using the Google Client Login API, we can start registering a cloud printer.We will register using the GCP /register endpoint:

	http://www.google.com/cloudprint/interface/register

Here is our code sample for registering using the Zend framework:
 The Google Cloud Print /register endpoint accepts the following parameters:

	printer - User readable name of the printer being registered (need not be unique).proxy - Identification of the printer client or proxy (must be unique).</p>
<center><p><a href="http://apievangelist.com/2011/02/06/google-cloud-print-register/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

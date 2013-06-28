---
layout: post
title: Google Cloud Print - Register
url: http://apievangelist.com/2011/02/06/google-cloud-print-register/
source: http://apievangelist.com/2011/02/06/google-cloud-print-register/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}Now that we are authenticated with a specific users Google Account using the Google Client Login API, we can start registering a cloud printer.
We will register using the GCP /register endpoint:

	http://www.google.com/cloudprint/interface/register

Here is our code sample for registering using the Zend framework:
 The Google Cloud Print /register endpoint accepts the following parameters:

	printer - User readable name of the printer being registered (need not be unique).
	proxy - Identification of the printer client or proxy (must be unique).
	capabilities - Printer capabilities (XPS or PPD).
	defaults - Printer default settings (XPS or PPD).
	status - Status string of the printer—e.g., Out of Paper, Online, etc.
	description - Descriptive string about the printer.
	capsHash - A hash or digest value of the capabilities data. This value is useful, for example, to compare values and check whether the local printer's capabilities have changed.

I am using the PPD format for the printer capabilities, in the future I will explore the usage of XPS.  Here is an example JSON response:
You now have the cloud printer ID for your registered Google Cloud Printer.  Users can add the printer as a Google Cloud Printer Proxy and send print jobs to it.
With the printer ID of your new Google Cloud Printer you can manage the printers status, capabilities, and print jobs from users.
Related articles

	Introduction to the Google Cloud Print Services Interface (kinlane.com)
	Google Cloud Print lets you print GMail content from your mobile device (macworld.com)
	Google to offer cloud printing for Chrome OS, web apps - predicts "cloud-aware" printers [TNW Google] (thenextweb.com)


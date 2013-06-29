---
layout: post
title: Mobile Data Gathering
url: http://kinlane.com/2009/12/15/mobile-data-gathering/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
While playing around with Google Fusion Tables tonight I came across the Open Data Kit (ODK).
Open Data Kit (ODK) is a suite of tools to help organizations collect, aggregate and visualize their data. The project's goals are to make open-source and standards-based tools which are easy to try, easy to use, easy to modify and easy to scale.
The project consists of:

	ODK Collect - ODK Collect is powerful phone based replacement for your paper forms. Collect is built on the Android
	ODK Aggregate - ODK Aggregate provides a ready to deploy online repository to store, view and export collected data. Aggregate is currently implemented on Google App Engine and enables free hosting of data on Google's reliable infrastructure.
	ODK Manage - ODK Manage maintains a database of all phones in a deployment to enable remote device management. By sending an SMS to a deployed phone, Manage can trigger the transfers of forms, data, and applications.
	ODK Validate - ODK Validate ensures that you have a OpenRosa complaint form -- one that will also work with all the ODK tools.
	ODK Voice - ODK Voice facilities mapping XForms to sound snippets that can be played over a "robo" call to any phone. Responses are collected using the phone's keypad (DTMF) and are automatically aggregated.

Cool stuff!
Great way to build mobile survey and data gathering applications that can be easily downloaded onto mobile phones such as Google Android.

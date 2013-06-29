---
layout: post
title: Federated Login for Google Account Users
url: http://kinlane.com/2008/12/17/federated-login-for-google-account-users/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
I have been working on a prototype for using the Federated Google Account login that uses the OpenID 2.0 standard.  Really a nice concept to offer for users who are heavy users of Google, Yahoo or other 3rd party service providers that have adopted OpenID.
I am proposing offering a Login Using Google button on all our public application logins which then send a request to Google and allows the user to authenticate our domain(s) under their Google Account.
Then they can utilize a single click login in the future without remembering yet another username and password.
It is really slick I recommend checking out the Google Federated Login information as well as reading up on the OpenID Standard.
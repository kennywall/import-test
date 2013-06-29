---
layout: post
title: Create a Cloud Printer with Box net
url: http://kinlane.com/2011/03/09/create-a-cloud-printing-with-box-net/
image: http://kinlane-productions.s3.amazonaws.com/box-net-logo.jpg
---
{% include JB/setup %}
A while back I was playing around with the Box.net API, I wanted to see what services they offered.
I created a set of PHP scripts for proofing Box.net files at Mimeo and preparing for printing.
At the same time I discovered their OpenBox platform.  OpenBox allows me to add applications to the Box.net platform and create associated actions with my application.
When a user adds an OpenBox application, the actions for that application are available in their Box.net account.
Using my Box.net developer account:

	I added a new application with Box.net.
	I call my application Cloud Report Printer
	I give the application a description and image.
	I add an action called Print Report @ Mimeo with a callback URL to the script I wrote for proofing Box.net files at Mimeo.

I can share the URL of my application with users and keep private or publish to directory, either way users can add my Cloud Report Printer to their Box.net account.

Then when editing a document, they have an action called Print Report @ Mimeo.
I've just created a prototype for a cloud printing and publishing application with Box.net
I can mix and match different types of documents at Mimeo and create an application at Box.net to print to them at Mimeo.
This opens up a lot of possibilities.
I will have other cloud printer prototypes that run on Box.net and print to Mimeo.com in the near future.

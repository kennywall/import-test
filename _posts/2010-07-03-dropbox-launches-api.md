---
layout: post
title: Dropbox Launches API
url: http://apievangelist.com/2010/07/03/dropbox-launches-api/
source: http://apievangelist.com/2010/07/03/dropbox-launches-api/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/cloud-computing/DropBox-Developers.PNG
---
{% include JB/setup %}Dropbox just launched a new application programming interface (API) for their popular cloud storage platform. The RESTful API allows you to exchange, distribute or access files on a user's desktop.
The API offers the following features:

	Simple HTTP+JSON method of accessing a user's information in a user approved sandbox on the user's desktop. List, upload, delete, move, copy, and get files as well as many other features.
	 A full event callback API allowing you to get simple asynchronous events to your web site or service whenever the user changes their sandbox. The events are designed to be tight and fast and easy to handle if you can receive HTTP requests and parse JSON.
	Implementations in Java, Ruby, Python, and Objective-C that are being actively used, and all MIT licensed.

You can tell their API deployment is fully baked and offers a complete set of support tools:

	Overview of the API
	Quick Start
	Announcement Area
	My Applications
	Mobile Documentation
	Client Libraries
	Bug Report

It is a well done implementation of a cloud storage API. I will review in more detail and compare against other popular standards like Amazon S3, Google Storage for Developers, and see how close it is to being a quality standard for a cloud storage API.
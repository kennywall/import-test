---
layout: post
title: "Dropbox Launches API"
url: 'http://kinlane.com/2010/07/03/dropbox-launches-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/cloud-computing/DropBox-Developers.PNG'
---

[<img class="alignnone c1" title="Dropbox" src="http://kinlane-productions.s3.amazonaws.com/cloud-computing/DropBox-Developers.PNG" alt="" width="250" height="97" align="right" />Dropbox just launched a new application programming interface (API)][1] for their popular cloud storage platform. The [RESTful API][2] allows you to exchange, distribute or access files on a user's desktop.

The API offers the following features:

  * Simple HTTP JSON method of accessing a user's information in a user approved sandbox on the user's desktop. List, upload, delete, move, copy, and get files as well as many other features.
  * A full event callback API allowing you to get simple asynchronous events to your web site or service whenever the user changes their sandbox. The events are designed to be tight and fast and easy to handle if you can receive HTTP requests and parse JSON.
  * Implementations in Java, Ruby, Python, and Objective-C that are being actively used, and all MIT licensed.
You can tell their API deployment is fully baked and offers a complete set of support tools:
  * Overview of the API
  * Quick Start
  * Announcement Area
  * My Applications
  * Mobile Documentation
  * Client Libraries
  * Bug Report
It is a well done implementation of a cloud storage API. I will review in more detail and compare against other popular standards like [Amazon S3][3], [Google Storage for Developers][4], and see how close it is to being a quality [standard for a cloud storage API][5].

   [1]: http://kinlane-productions.s3.amazonaws.com/cloud-computing/DropBox-Developers.PNG
   [2]: http://en.wikipedia.org/wiki/Representational_State_Transfer
   [3]: http://www.kinlane.com/category/amazon/amazon-s3/
   [4]: http://www.kinlane.com/category/google/google-storage-for-developers/
   [5]: http://www.kinlane.com/2010/06/cloud-storage-api-standard/

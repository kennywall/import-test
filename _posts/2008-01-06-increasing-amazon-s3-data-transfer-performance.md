---
layout: post
title: Increasing Amazon S3 Data Transfer Performance
url: http://kinlane.com/2008/01/06/increasing-amazon-s3-data-transfer-performance/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
The Amazon S3 team is now beta-testing support for an important low-level networking feature which has the potential to significantly increase the performance of large data transfers to and from S3, particularly for long distance data transfers.Per the thread in the Amazon S3 Forum, early results from the beta testers are quite good with reported speedups of 4x to 18x! If you are moving large amounts of data into or out of S3 then you will definitely want to implement this feature.For me the Amazon S3 performance has be acceptable for 90% of my projects, however I have had a few clients who chose not to use the service when they complained about performance speeds during prototyping.Eager to see what the Amazon Team comes up wtih.
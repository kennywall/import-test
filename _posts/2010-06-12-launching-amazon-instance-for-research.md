---
layout: post
title: Launching Amazon Instance for Research
url: http://kinlane.com/2010/06/12/launching-amazon-instance-for-research/
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}
I'm launching a new Amazon EC2 instance. Its running Windows + PHP + MySQL. Its a preset up instance AMI I have for harvesting data.
Its setup with necessary harvest scripts with all my libraries setup just for pulling RSS, XML, and scraping HTML pages.
I'm doing some research about how to grow my Google Reader network based upon users who read and liked other posts that I liked.
I'll leave my Amazon EC2 instance up while I'm running some harvest scripts.
Next I will cleanup and warehouse the data I pulled.
Once I'm done I'll backup MySQL and store at Amazon S3 for next time I"m working on this project.
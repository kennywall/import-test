---
layout: post
title: Using Amazon EBS Volumes
url: http://kinlane.com/2010/06/16/learning-more-about-amazon-ebs-volumes/
image: http://d1nqddva888cns.cloudfront.net/EBS_Free_Monitoring_Console.png
---
{% include JB/setup %}

I'm taking another look at them. I'm going to use in a couple different scenarios:

	AMI Root Device Type - I'm switching all of my Amazon Machine Images to be EBS Root Device Type. This will help with faster launching and persistence of the AMI.
	Second Instance Drive - Many of the instances I deploy use the C: drive as the system, and D:, E: and other drives as secondary data storage. I will start using EBS Volumes for all secondary drives.

I will still be using key Amazon S3 buckets for global storage of images, video, audio and other files that I use across servers and deliver to different availability zones worldwide.
Amazon just released CloudWatch Metrics for Amazon EBS Volumes, which should make my EBS deployments much easier to manage.
More to come as I further integrate Amazon EBS Volumes into my cloud IT infrastructure strategy.
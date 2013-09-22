---
layout: post
title: "Using Amazon EBS Volumes"
url: 'http://kinlane.com/2010/06/16/learning-more-about-amazon-ebs-volumes/'
image: 'http://d1nqddva888cns.cloudfront.net/EBS_Free_Monitoring_Console.png'
---

<img title="Amazon EBS Volume Metrics" src="http://d1nqddva888cns.cloudfront.net/EBS_Free_Monitoring_Console.png" alt="" width="300" align="right" class="c1" />I'm increasing my usage of Amazon EBS volumes. I tend to use objects I've written in PHP or ColdFusion for writing data to Amazon S3. I haven't historically used EBS volumes much, because data tends to be needed across multiple instances.

I'm taking another look at them. I'm going to use in a couple different scenarios:

  * **AMI Root Device Type** \- I'm switching all of my Amazon Machine Images to be EBS Root Device Type. This will help with faster launching and persistence of the AMI.
  * **Second Instance Drive** \- Many of the instances I deploy use the C: drive as the system, and D:, E: and other drives as secondary data storage. I will start using EBS Volumes for all secondary drives.
I will still be using key [Amazon S3][1] buckets for global storage of images, video, audio and other files that I use across servers and deliver to different availability zones worldwide.

Amazon just released [CloudWatch Metrics for Amazon EBS Volumes,][2] which should make my EBS deployments much easier to manage.

More to come as I further integrate [Amazon EBS Volumes][3] into my [cloud IT infrastructure strategy][4].

   [1]: http://www.kinlane.com/category/amazon/amazon-s3/
   [2]: http://aws.typepad.com/aws/2010/06/new-cloudwatch-metrics-for-amazon-ebs-volumes.html
   [3]: http://aws.amazon.com/ebs/
   [4]: http://www.kinlane.com

---
layout: post
title: "Host Your Entire Website at Amazon S3"
url: 'http://kinlane.com/2011/02/18/host-your-entire-website-at-amazon-s3/'
image: 'http://kinlane-productions.s3.amazonaws.com/amazon/Run-Website-On-Amazon-S3.png'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/amazon/Run-Website-On-Amazon-S3.png" alt="" width="300" align="right" />][1]Amazon made some more tweaks to [Amazon S3][2] that make it even easier to [host your entire static web site at Amazon S3][3].

In addition to hosting images, video at Amazon S3, you can store all your static site files like CSS, JavaScript, and HTML on the cloud storage platform.

Some of the new features include:

  * Website endpoints for US Standard, US West, EU, or Asia Pacific regions
  * Returns a root document for each bucket
  * Returns HTML error document instead of XML error message
  * Custom error documents for specific error codes.
You can enable your bucket as a website using the following tools:
  * S3 tab of the [AWS Management Console][4]
  * [CloudBerry S3 Explorer][5]
  * [Bucket Explorer][6]
  * AWS Java, .NET, and PHP SDK's
You can expect popular CMS platforms like [Wordpress][7], [Moveable Type][8], and [Drupal][9] to start publishing all images and site content to Amazon S3.

This would allow site owners to to take advantage of the low cost storage, scalability, and global distribution provided by Amazon S3

Amazon CTO [Werner Vogels][10] is already running his [All Things Distributed][1] blog completely on Amazon S3.

   [1]: http://www.allthingsdistributed.com/
   [2]: http://aws.amazon.com/s3/
   [3]: http://aws.typepad.com/aws/2011/02/host-your-static-website-on-amazon-s3.html
   [4]: http://aws.amazon.com/console/
   [5]: http://cloudberrylab.com/?page=cloudberry-explorer-amazon-s3
   [6]: http://www.bucketexplorer.com/
   [7]: http://wordpress.org/
   [8]: http://www.movabletype.org/
   [9]: http://drupal.org/
   [10]: http://www.allthingsdistributed.com (Werner Vogels)

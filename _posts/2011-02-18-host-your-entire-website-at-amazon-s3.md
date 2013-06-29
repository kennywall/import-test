---
layout: post
title: Host Your Entire Website at Amazon S3
url: http://kinlane.com/2011/02/18/host-your-entire-website-at-amazon-s3/
image: http://kinlane-productions.s3.amazonaws.com/amazon/Run-Website-On-Amazon-S3.png
---
{% include JB/setup %}
<p>
     Amazon made some more tweaks to Amazon S3 that make it even easier to host your entire static web site at Amazon S3. In addition to hosting images, video at Amazon S3, you can store all your static site files like CSS, JavaScript, and HTML on the cloud storage platform. Some of the new features include: Website endpoints for US Standard, US West, EU, or Asia Pacific regions Returns a root document for each bucket Returns HTML error document instead of XML error message Custom error documents for specific error codes. You can enable your bucket as a website using the following tools: S3 tab of the AWS Management Console CloudBerry S3 Explorer Bucket Explorer AWS Java, .NET, and PHP SDK's You can expect popular CMS platforms like Wordpress, Moveable Type, and Drupal to start publishing all images and site content to Amazon S3. This would allow site owners to to take advantage of the low cost storage, scalability, and global distribution provided by Amazon S3 Amazon CTO Werner Vogels is already running his All Things Distributed blog completely on Amazon S3.
</p>
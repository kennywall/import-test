---
layout: post
title: Amazon S3 - Access Logging
url: http://apievangelist.com/2010/06/28/amazon-s3-access-logging/
source: http://apievangelist.com/2010/06/28/amazon-s3-access-logging/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/amazon/Amazon-S3-Logging.PNG
---
{% include JB/setup %}I was mapping some subdomains to various Amazon S3 buckets today. I decided to use the new Amazon S3 interface available in the Amazon Console, instead of S3Fox for a change.
I was setting the permissions for a new bucket and I noticed the logging feature for each bucket. For some reason this has escaped me. I see in the developers area that S3 Logging has been around for years?

Anyways, you can set access logging for each bucket. Seems like a perfect feature to help deal with security concerns about storing data in the clouds. The logging feature is a great tool if you are required keep detailed logs of who accessed your data.
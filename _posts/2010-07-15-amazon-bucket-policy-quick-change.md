---
layout: post
title: Amazon Bucket Policy Quick Change
url: http://apievangelist.com/2010/07/15/amazon-bucket-policy-quick-change/
source: http://apievangelist.com/2010/07/15/amazon-bucket-policy-quick-change/
domain: apievangelist.com
image: http://images.cloudberrylab.com/Content_01.gif
---
{% include JB/setup %}I have several Amazon Buckets I quickly want to use for public viewing of images and other files for clients. I haven't had time to integrate the bucket policy API into our code base. I just need the buckets updated right away for GETOBJECT for all public users.
I logged into the Amazon Console and right clicked on the properties for the bucket. Just ACL functionality here.
I then opened up my CloudBerry Explorer Pro and right clicked on a bucket. They have a bucket policy property for all buckets. Way to be on the ball CloudBerry, you guys seem to be the most agile player in the cloud storage game at the moment.
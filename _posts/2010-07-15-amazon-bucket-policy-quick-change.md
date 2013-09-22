---
layout: post
title: "Amazon Bucket Policy Quick Change"
url: 'http://kinlane.com/2010/07/15/amazon-bucket-policy-quick-change/'
image: 'http://images.cloudberrylab.com/Content_01.gif'
---

<img class="alignnone" title="Cloudberry Labs" src="http://images.cloudberrylab.com/Content_01.gif" alt="" width="209" height="54" align="right" />I have several Amazon Buckets I quickly want to use for public viewing of images and other files for clients. I haven't had time to integrate the [bucket policy API][1] into our code base. I just need the buckets updated right away for GETOBJECT for all public users.

I logged into the [Amazon Console][2] and right clicked on the properties for the bucket. Just ACL functionality here.

I then opened up my [CloudBerry Explorer Pro][3] and right clicked on a bucket. They have a bucket policy property for all buckets. Way to be on the ball [CloudBerry][4], you guys seem to be the most agile player in the [cloud storage][4] game at the moment.

   [1]: http://www.kinlane.com/2010/07/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/
   [2]: http://www.kinlane.com/category/amazon/amazon-console/
   [3]: http://cloudberrylab.com/?page=s3-explorer-pro
   [4]: http://cloudberrylab.com/

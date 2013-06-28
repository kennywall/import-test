---
layout: post
title: Securing Global Content With Amazon S3 Bucket Policies
url: http://kinlane.com/2010/07/08/securing-global-content-with-amazon-s3-bucket-policies/
source: http://kinlane.com/2010/07/08/securing-global-content-with-amazon-s3-bucket-policies/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/cloud-computing/global-digital_delivery.jpg
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <img class="alignnone" style="padding: 15px;" title="Secure Global Content Delivery" src="http://kinlane-productions.s3.amazonaws.com/cloud-computing/global-digital_delivery.jpg" alt="" width=
    "275" align="right" />I'm spending a lot of time lately looking at more efficient and secure ways of delivery web applications and content globally. I am refining my DNS strategy using <a href=
    "http://www.kinlane.com/2010/07/cloud-balancing-with-global-server-load-balancer-gslb/">Global Server Load Balancing</a> (GSLB), and refining my file and <a href=
    "http://www.kinlane.com/2010/07/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/">content management policies now that Amazon Web Services is offering Bucket
    Policies</a>. <strong>Geographic Specific Sub-Domains (CNAME)</strong> With <a href="http://www.kinlane.com/category/global-server-load-balancing/">Global Server Load Balancing</a> I can setup
    geographically specific sub-domains like eu.domain.com and us-west.domain.com that are bound to specific Amazon S3 buckets and <a href=
    "http://www.kinlane.com/category/amazon/amazon-cloudfront/">Amazon Cloudfront Distributions</a>. <strong>Secure Files and Content with Bucket Policies</strong> Now with <a href=
    "http://www.kinlane.com/2010/07/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/">Amazon Bucket Policies</a> I can restrict access to buckets for reading or
    writing to specific domain names, IP Addresses, or IP Ranges. Not only can I distribute my files and content to Amazon Edge Locations in US, Europe, Hong Kong, and Japan. With the addition of
    Amazon S3 bucket policies I can secure specific objects and buckets of objects to ensure they are only delivered within geographic regions that are acceptable. If there are legal or regulatory
    considerations for videos, audio or other file types, I can enforce policies through my Global Server Load Balancing, Amazon S3 Bucket Policies, and Amazon Cloudfront Distributions. You can
    really get granular about <a href="http://www.kinlane.com/2010/06/do-you-know-where-your-data-is-in-the-cloud/">where your data is distributed and what geographic regions can access your
    data</a>.
  </body>
</html></p>

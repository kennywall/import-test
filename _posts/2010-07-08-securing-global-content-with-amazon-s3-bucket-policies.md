---
layout: post
title: Securing Global Content With Amazon S3 Bucket Policies
url: http://kinlane.com/2010/07/08/securing-global-content-with-amazon-s3-bucket-policies/
image: http://kinlane-productions.s3.amazonaws.com/cloud-computing/global-digital_delivery.jpg
---
{% include JB/setup %}
I'm spending a lot of time lately looking at more efficient and secure ways of delivery web applications and content globally. I am refining my DNS strategy using Global Server Load Balancing (GSLB), and refining my file and content management policies now that Amazon Web Services is offering Bucket Policies.
Geographic Specific Sub-Domains (CNAME)
With Global Server Load Balancing I can setup geographically specific sub-domains like eu.domain.com and us-west.domain.com that are bound to specific Amazon S3 buckets and Amazon Cloudfront Distributions.
Secure Files and Content with Bucket Policies
Now with Amazon Bucket Policies I can restrict access to buckets for reading or writing to specific domain names, IP Addresses, or IP Ranges.
Not only can I distribute my files and content to Amazon Edge Locations in US, Europe, Hong Kong, and Japan. With the addition of Amazon S3 bucket policies I can secure specific objects and buckets of objects to ensure they are only delivered within geographic regions that are acceptable. If there are legal or regulatory considerations for videos, audio or other file types, I can enforce policies through my Global Server Load Balancing, Amazon S3 Bucket Policies, and Amazon Cloudfront Distributions.
You can really get granular about where your data is distributed and what geographic regions can access your data.
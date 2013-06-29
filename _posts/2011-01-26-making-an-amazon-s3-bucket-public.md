---
layout: post
title: Making an Amazon S3 Bucket Public
url: http://kinlane.com/2011/01/26/making-an-amazon-s3-bucket-public/
image: http://a0.twimg.com/profile_images/1176550371/5163129933_353fc10a38_m_normal.jpg
---
{% include JB/setup %}




@audreywatters -I don't know how to manage my bucket policies cc @kinlane







@kinlane -@audreywatters go to aws console -&gt; find folder -&gt; edit properties -&gt; permissions -&gt; edit bucket policy. I will email policy to you.



Paste this bucket policy with [bucket name] changed to your bucket name.
 {
"Version": "2008-10-17",
"Id": "57eafc04-1a5c-479b-8106-01828c991cd3",
"Statement": [
{
"Sid": "AddPerm",
"Effect": "Allow",
"Principal": {
"AWS": "*"
},
"Action": "s3:GetObject*",
"Resource": "arn:aws:s3:::[bucket name]/*"
}
]
}

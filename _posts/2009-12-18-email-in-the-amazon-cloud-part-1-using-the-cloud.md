---
layout: post
title: Email in the Amazon Cloud Part 1 Using the Cloud
url: http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-1-using-the-cloud/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}

They just offered the computing and storage power I needed with Amazon EC2 and Amazon S3. Plus the opportunity of using more services like Amazon SimpleDB and Amazon Cloudfront.
So I moved us over. It took me 2 months to migrate from three extremely overloaded servers a platform that we could grow from. Amazon EC2 and Amazon S3 let me really balance out our load and really get a solid base up and running quickly.
Beyond our base need for web, databases, ftp, version control, and web services, we had high needs for volume email and more specifically SMTP services.
So I started evaluating how we sent mail and got to work at optimizing this process for scaling email for large blasts.
Email in the Amazon Cloud - Part 1 - Part 2 - Part 3 - Part 4 - Part 5 - Part 6 - Guide to Email in the Amazon Cloud
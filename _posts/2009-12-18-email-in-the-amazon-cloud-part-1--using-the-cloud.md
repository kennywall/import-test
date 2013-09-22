---
layout: post
title: "Email in the Amazon Cloud Part 1 - Using the Cloud"
url: 'http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-1-using-the-cloud/'
image: ''
---

Amazon is a great place to really take care of business when it comes to IT. First order of business at my new job last year was to take care of a really troubling "hostage" situation with their current server co-location contract. My boss said, "move us to the cloud". I had used Amazon Web Services before, I thought I should check out other providers as well. So I toured a handful of cloud providers, but ended up back with Amazon Web Services.

They just offered the computing and storage power I needed with [Amazon EC2][1] and [Amazon S3][2]. Plus the opportunity of using more services like [Amazon SimpleDB][3] and [Amazon Cloudfront][4].

So I moved us over. It took me 2 months to migrate from three extremely overloaded servers a platform that we could grow from. [Amazon EC2][4] and [Amazon S3][2] let me really balance out our load and really get a solid base up and running quickly.

Beyond our base need for web, databases, ftp, version control, and web services, we had high needs for volume email and more specifically SMTP services.

So I started evaluating how we sent mail and got to work at optimizing this process for [scaling email for large blasts][5].

**Email in the Amazon Cloud** \- [Part 1][6] \- [Part 2][5] \- [Part 3][7] \- [Part 4][8] \- [Part 5][9] \- [Part 6][10] \- [Guide to Email in the Amazon Cloud][11]

   [1]: http://aws.amazon.com/ec2/
   [2]: http://aws.amazon.com/s3/
   [3]: http://aws.amazon.com/simpledb/
   [4]: http://aws.amazon.com/cloudfront/
   [5]: http://www.kinlane.com/?p=1098
   [6]: http://www.kinlane.com/?p=1095
   [7]: http://www.kinlane.com/?p=1100
   [8]: http://www.kinlane.com/?p=1102
   [9]: http://www.kinlane.com/?p=1104
   [10]: http://www.kinlane.com/?p=1106
   [11]: http://www.kinlane.com/2010/07/email-infrastructure-in-the-amazon-cloud/

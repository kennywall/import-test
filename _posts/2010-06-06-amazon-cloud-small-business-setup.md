---
layout: post
title: "Amazon Cloud Small Business Setup"
url: 'http://kinlane.com/2010/06/06/amazon-cloud-small-business-setup/'
image: 'http://awsmedia.s3.amazonaws.com/logo_aws.gif'
---

<img class="c1" title="Amazon Web Services" src="http://awsmedia.s3.amazonaws.com/logo_aws.gif" alt="" width="164" height="60" align="right" />I have been in the [Amazon Console][1] all night scaling down infrastructure after 3 months of events and conferences. This year our Amazon spend was double during the event season. Last year I pushed what my budget would allow to achieve better performance, it paid off. This year I got the thumbs up to push even further (even though I think I may have pushed a little further than I should have), with the amount to spend on processor power.

Anyways, while data was moving around and [Amazon Machine Images (AMI)][2] were being created last night I was playing in the [Amazon Console][1]. I really think the Amazon platform is really ready for mainstream small business cloud deployments.

Most small business I have worked with have minimal needs regarding Internet technologies that fall under these areas:

  * Server / Processing Power
  * File Storage and Access
  * Email
  * Load Balancing for scaling but mostly for maintenance and redundancy.
  * Backup
  * Database
That would cover most of the needs for 75% of the small businesses I've worked with. Now these are usually business with 5-200 employees and less than 25 Million in revenue. Amazon has really brought together a set of tools that can deliver a complete package for small business:
  * Serve / Processing Power with [Amazon EC2][3]
  * File Storage and Access with [Amazon S3][4]
  * Email with [Amazon EC2][3] and [Simple Notification (SNS)][4]
  * Load Balancing with [Amazon Auto Scaling][5] and [Elastic Load Balancing][6]
  * Backups with [Amazon Machine Images (AMI)][2] and backup storage at [Amazon S3][4]
  * Database with [Amazon EC2][3], [Amazon Simple Database][7] or [Amazon Relational Database (RDS)][8]
Most of these tools are available within the [Amazon Console][1], and everything is available programatically through the Amazon Web Services API. I run our entire business in the cloud. My company WebEvents Global has some unique needs around scaling our infrastructure for events, but beyond that it is a pretty standard business operation.

I see a clear vision of how a company can completely operate in the clouds and really define their IT operations, establish benchmarks for what things costs, and take control over their IT infrastructure and make it scalable and resilient in many ways through deploying to the Amazon cloud.

I'm going to keep writing on this subject as more and more small to medium business are looking to move on to the cloud.

   [1]: http://aws.amazon.com/console/
   [2]: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=171
   [3]: http://aws.amazon.com/ec2/
   [4]: http://aws.amazon.com/s3/
   [5]: http://aws.amazon.com/autoscaling/
   [6]: http://aws.amazon.com/elasticloadbalancing/
   [7]: http://aws.amazon.com/simpledb/
   [8]: http://aws.amazon.com/rds/

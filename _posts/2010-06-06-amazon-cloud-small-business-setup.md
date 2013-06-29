---
layout: post
title: Amazon Cloud Small Business Setup
url: http://kinlane.com/2010/06/06/amazon-cloud-small-business-setup/
image: http://awsmedia.s3.amazonaws.com/logo_aws.gif
---
{% include JB/setup %}

Anyways, while data was moving around and Amazon  Machine Images (AMI) were being created last night I was playing in the Amazon Console.   I really think the Amazon platform is really ready for mainstream small business cloud deployments.
Most small business I have worked with have minimal needs regarding Internet technologies that fall under these areas:

	Server / Processing Power
	File Storage and Access
	Email
	Load Balancing for scaling but mostly for maintenance and redundancy.
	Backup
	Database

That would cover most of the needs for 75% of the small businesses I've worked with.  Now these are usually business with 5-200 employees and less than 25 Million in revenue.  Amazon has really brought together a set of tools that can deliver a complete package for small business:

	Serve / Processing Power with Amazon EC2
	File Storage and Access with Amazon S3
	Email with Amazon EC2 and Simple Notification (SNS)
	Load Balancing with Amazon Auto Scaling and Elastic Load Balancing
	Backups with Amazon Machine Images (AMI) and backup storage at Amazon  S3
	Database with Amazon EC2, Amazon Simple Database or Amazon Relational Database (RDS)

Most of these tools are available within the Amazon Console, and everything is available programatically through the Amazon Web Services API. I run our entire business in the cloud. My company WebEvents Global has some unique needs around scaling our infrastructure for events, but beyond that it is a pretty standard business operation.
I see a clear vision of how a company can completely operate in the clouds and really define their IT operations, establish benchmarks for what things costs, and take control over their IT infrastructure and make it scalable and resilient in many ways through deploying to the Amazon cloud.
I'm going to keep writing on this subject as more and more small to medium business are looking to move on to the cloud.
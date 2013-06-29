---
layout: post
title: Amazon EC2 Adds Change Instance Type and Shutdown Behavior
url: http://kinlane.com/2011/03/09/easier-scalability-with-aws/
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}
Amazon Web Services just released two pretty significationenhancementsto the Amazon EC2 infrastructure.
You can now:

	Change Instance Type -This means that you can scale up or scale down as your needs change. The new instance type must be compatible with the AMI that you used to boot the instance, so you can't change from 32 bit to 64 bit or vice versa.
	Shutdown Behavior -You can now control what happens when an EBS-backed instance shuts itself down. You can choose to stop the instance (so that it can be started again later) or to terminate the instance.

These are two pretty significant features when your working with 24/7, mission critical applications and database that run on EC2.
Gone are the days when you shut down an instance and its gone forever, thanks to EBS and the new and Amazon EC2.
Related articles

	Even More EC2 Goodies in the AWS Management Console (aws.typepad.com)
	Amazon Going PaaS? Introducing Elastic Beanstalk (web2.sys-con.com)
	AWS CloudFormation: Poaching The Ecosystem? (cloudave.com)


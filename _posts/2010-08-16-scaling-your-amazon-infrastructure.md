---
layout: post
title: Scaling Your Amazon Infrastructure
url: http://apievangelist.com/2010/08/16/scaling-your-amazon-infrastructure/
source: http://apievangelist.com/2010/08/16/scaling-your-amazon-infrastructure/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}<p>I am still processing a great post at High Scalability called, Scaling an AWS infrastructure - Tools and Patterns.They cover several tools you can use to take advantage of Amazons Web Service and suggest an architectural model you should adopt for a scalable infrastructure in the cloud.They suggest the following tools for managing your amazon scaling:

	Puppet for managing your Amazon EC2 instances
	Capistrano for cloud task automation
	Centreon/Nagios, Zabbix, Cacti and Munin for cloud monitoring
	Syslog-NG for centralized log file management

They even cover several tools for optimized data access:

	Structured relational data with MySQL or a PgSQL on Amazon EC2
	Storage for more volatile data with tools like Redis, Tokyo Tyrant/Tokyo Cabinet, MemcacheDB.There are a lot of great points on how to scale your Amazon Cloud infrastructure.Exciting to see different approaches to scaling with Amazon Ec2 and S3 and throwing in some innovative open source tools that make the process much easier and powerful.</p>
<center><p><a href="http://apievangelist.com/2010/08/16/scaling-your-amazon-infrastructure/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

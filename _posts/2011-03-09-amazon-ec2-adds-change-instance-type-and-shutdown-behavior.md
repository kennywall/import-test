---
layout: post
title: "Amazon EC2 Adds Change Instance Type and Shutdown Behavior"
url: 'http://kinlane.com/2011/03/09/easier-scalability-with-aws/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />**Amazon Web Services** just released two pretty [significationenhancementsto the Amazon EC2 infrastructure][1].

You can now:

  * **Change Instance Type** -This means that you can scale up or scale down as your needs change. The new instance type must be compatible with the AMI that you used to boot the instance, so you can't change from 32 bit to 64 bit or vice versa.
  * **Shutdown Behavior** -You can now control what happens when an EBS-backed instance shuts itself down. You can choose to stop the instance (so that it can be started again later) or to terminate the instance.
These are two pretty significant features when your working with 24/7, mission critical applications and database that run on EC2.

Gone are the days when you shut down an instance and its gone forever, thanks to EBS and the new and Amazon EC2.

######  Related articles

  * [Even More EC2 Goodies in the AWS Management Console][2] (aws.typepad.com)
  * [Amazon Going PaaS? Introducing Elastic Beanstalk][3] (web2.sys-con.com)
  * [AWS CloudFormation: Poaching The Ecosystem?][4] (cloudave.com)

   [1]: http://aws.typepad.com/aws/2011/03/even-more-ec2-goodies-in-the-aws-management-console.html (Amazon EC2 Enhancements)
   [2]: http://aws.typepad.com/aws/2011/03/even-more-ec2-goodies-in-the-aws-management-console.html
   [3]: http://web2.sys-con.com/node/1687874
   [4]: http://www.cloudave.com/10183/aws-cloudformation-poaching-the-ecosystem/

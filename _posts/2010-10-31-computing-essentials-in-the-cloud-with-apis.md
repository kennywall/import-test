---
layout: post
title: "Computing Essentials in the Cloud with APIs"
url: 'http://kinlane.com/2010/10/31/computing-essentials-in-the-cloud-with-apis/'
image: 'http://kinlane-productions.s3.amazonaws.com/cloud.jpeg'
---

As we continue to move computing off the workstation and servers and into the cloud, we need to recreate all the essentials of computing we are used to. APIs are how the next generation of computing essentials like email, print, DNS, and file system will be delivered in this environment.

As we distribute and virtualize our web sites, applications and other tools, APIs are playing an ever more increasing role in connecting these applications for us. A couple examples are:

  * **Email with [Mailgun][1]:** Mailgun provides a [RESTFul Email API][1] for fully managed, scalable email servers.
  * <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/cloud.jpeg" alt="" width="250" align="right" />
  * **Print with [Mimeo Connect][2]:** Mimeo Connect provides a [REST and SOAP Print API][2] for web to print integration for applications.
  * **DNS with [Zerigo][3]:** Zerigo provides a [RESTFUL DNS API][3] to manage DNS for your applications.
  * **Files with [Amazon S3][4]:** Amazon S3 provides an [REST object storage API][4] that can be used as a file system and CDN.
APIs allow developers to off-load specific computing tasks to third party providers who specialize in these areas. APIs can deliver speedier development, and support widely distributed system by communicating using XML and JSON, and provide security using standards like OAuth.

We will see more computing essentials like print and email exposed online via open APIs for integration into mobile and web applications.

APIs provide the data and functionality needed to drive the next generation of computing that will occur primarily in the clouds via mobile interfaces.

   [1]: http://www.mailgun.net/
   [2]: http://www.mimeo.com/solutions/mimeo-connect.php
   [3]: http://www.zerigo.com/
   [4]: http://aws.amazon.com/s3/

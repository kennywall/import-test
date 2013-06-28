---
layout: post
title: Internet Service Provider (ISP) at Amazon Web Services (AWS)
url: http://kinlane.com/2010/08/07/internet-service-provider-isp-at-amazon-web-services-aws/
source: http://kinlane.com/2010/08/07/internet-service-provider-isp-at-amazon-web-services-aws/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <img class="alignnone" style="padding: 15px;" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />I was just
    refining a wiki page of various building blocks I use at Amazon Web Services. I noticed it would make a great Internet Service Provider (ISP) package for someone who wanted to start an ISP, or
    even used as model for an existing ISP looking to migrate to cloud computing. These are a few of the components I have my list:
    <ul class="mainlist">
      <li>Web Server on Amazon EC2
        <ul class="mainlist">
          <li>Linux / Windows
          </li>
          <li>EBS Volumes for Storage
          </li>
          <li>Machine Images
          </li>
        </ul>
      </li>
      <li>Amazon S3 Central File Storage + Jungle Disk
        <ul class="mainlist">
          <li>Server Backup
          </li>
          <li>Central File Storage
          </li>
          <li>Client Cloud Storage as a Service
          </li>
          <li>FTP Access
          </li>
        </ul>
      </li>
      <li>Database
        <ul class="mainlist">
          <li>SQL Server 2008
          </li>
          <li>MySQL
          </li>
          <li>Amazon RDS
          </li>
          <li>Other (Amazon SimpleDB, Cassandra, CouchDB, etc)
          </li>
        </ul>
      </li>
      <li>Email
        <ul class="mainlist">
          <li>POP Server
          </li>
          <li>SMTP Server
          </li>
        </ul>
      </li>
      <li>DNS Server
      </li>
      <li>FTP Server
        <ul class="mainlist">
          <li>Web File Access
          </li>
          <li>Central File Storage Access
          </li>
        </ul>
      </li>
      <li>SVN Server
        <ul class="mainlist">
          <li>Version Repositories
          </li>
          <li>Client Checkout
          </li>
        </ul>
      </li>
    </ul>These are just a few of the building blocks I have on my list. There are many other possibilities and configurations. You slap on an ISP Cloud Management tool like <a href=
    "http://www.parallels.com/store/plesk/" target="_blank">Plesk from Parallels</a> and you can manage your network without much headache. You are going to see many Internet Service Providers (ISP)
    make the jump to the cloud because of cost and ease of deployment. There are just too many benefits to ignore the cloud.
  </body>
</html></p>

---
layout: post
title: "Scaling Your Amazon Infrastructure"
url: 'http://kinlane.com/2010/08/16/scaling-your-amazon-infrastructure/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

<img class="c1" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />I am still processing a great post at [High Scalability][1] called, [Scaling an AWS infrastructure - Tools and Patterns][2]. They cover several tools you can use to take advantage of Amazon's Web Service and suggest an architectural model you should adopt for a scalable infrastructure in the cloud.

They suggest the following tools for managing your amazon scaling:

  * [Puppet][3] for managing your Amazon EC2 instances
  * [Capistrano][4] for cloud task automation
  * [Centreon][5]/[Nagios][6], [Zabbix][7], [Cacti][8] and [Munin][9] for cloud monitoring
  * [Syslog-NG][10] for centralized log file management
They even cover several tools for optimized data access:
  * Structured relational data with MySQL or a PgSQL on Amazon EC2
  * Storage for more volatile data with tools like [Redis][11], [Tokyo Tyrant][12]/[Tokyo Cabinet][13], [MemcacheDB][14].
There are a lot of great points on how to scale your Amazon Cloud infrastructure. Exciting to see different approaches to scaling with Amazon Ec2 and S3 and throwing in some innovative open source tools that make the process much easier and powerful.

   [1]: http://highscalability.com/
   [2]: http://highscalability.com/blog/2010/8/16/scaling-an-aws-infrastructure-tools-and-patterns.html
   [3]: http://www.puppetlabs.com/
   [4]: http://www.capify.org/index.php/Capistrano
   [5]: http://www.centreon.com/ (Site de Centreon)
   [6]: http://www.nagios.org/ (Site de Nagios)
   [7]: http://www.zabbix.com/ (Site de Zabbix)
   [8]: http://www.cacti.net/ (Site de Cacti)
   [9]: http://munin.projects.linpro.no/ (Site de Munin)
   [10]: http://www.balabit.com/network-security/syslog-ng/ (Site de Syslog-NG)
   [11]: http://code.google.com/p/redis/ (Site de Redis)
   [12]: http://1978th.net/tokyotyrant/ (Site de Tokyo Tyrant)
   [13]: http://1978th.net/tokyocabinet/ (Site de Tokyo Cabinet)
   [14]: http://memcachedb.org/ (Site de MemcacheDB)

---
layout: post
title: "Role Based Server Architecture"
url: 'http://kinlane.com/2009/02/11/role-based-server-architecture/'
image: ''
---

I am really finding one consistent them across my cloud server architecture lately. It is was I am calling roles. These are server roles that meet specific business goals, such as:

  * [PHP][1] [Web Server][2]
  * [ColdFusion][3] Web Server
  * [.NET][4] Web Server
  * [SQL 2008][5] Database Server
  * [MySQL][6] Database Server
  * [SMTP][7] Server
  * POP Server
  * [DNS][8] Server
  * [FTP][9] Server
  * [Subversion][10] (SVN) Server
These are specific server roles that get my work done and allow teams and companies I work with to get their jobs done. Defining server instance roles allows me to designate specic machine purposes that I can deploy as Amazon Instances rapidly. I setup base server role instance machine images or Amazon Machine Images. I use these as the building blocks for my server infrastructure environment. Once I configure a machine role for a specific purpose I will then take another machine image...usually on a weekly bases to keep all that work and configuration in a need package for deployment and scaling. More to come on Cloud Based Server Role Infrastructure Deployment.

   [1]: http://php.net/ (PHP)
   [2]: http://en.wikipedia.org/wiki/Web_server (Web server)
   [3]: http://www.adobe.com/products/coldfusion (ColdFusion)
   [4]: http://www.microsoft.com/net/ (.NET Framework)
   [5]: http://www.microsoft.com/sqlserver/2008/en/us/ (Microsoft SQL Server)
   [6]: http://www.mysql.com (MySQL)
   [7]: http://en.wikipedia.org/wiki/Simple_Mail_Transfer_Protocol (Simple Mail Transfer Protocol)
   [8]: http://en.wikipedia.org/wiki/Domain_Name_System (Domain Name System)
   [9]: http://en.wikipedia.org/wiki/File_Transfer_Protocol (File Transfer Protocol)
   [10]: http://subversion.tigris.org/ (Subversion (software))

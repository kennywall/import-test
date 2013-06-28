---
layout: post
title: Role Based Server Architecture
url: http://apievangelist.com/2009/02/11/role-based-server-architecture/
source: http://apievangelist.com/2009/02/11/role-based-server-architecture/
domain: apievangelist.com
image: 
---
{% include JB/setup %}<p>I am really finding one consistent them across my cloud server architecture lately. It is was I am calling roles. These are server roles that meet specific business goals, such as:  PHP Web Server ColdFusion Web Server .NET Web Server SQL 2008 Database Server MySQL Database Server SMTP Server POP Server DNS Server FTP Server Subversion (SVN) Server  These are specific server roles that get my work done and allow teams and companies I work with to get their jobs done. Defining server instance roles allows me to designate specic machine purposes that I can deploy as Amazon Instances rapidly. I setup base server role instance machine images or Amazon Machine Images. I use these as the building blocks for my server infrastructure environment. Once I configure a machine role for a specific purpose I will then take another machine image...usually on a weekly bases to keep all that work and configuration in a need package for deployment and scaling. More to come on Cloud Based Server Role Infrastructure Deployment. </p>
<center><p><a href="http://apievangelist.com/2009/02/11/role-based-server-architecture/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

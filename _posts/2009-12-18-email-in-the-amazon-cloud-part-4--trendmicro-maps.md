---
layout: post
title: "Email in the Amazon Cloud Part 4 - TrendMicro Maps"
url: 'http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-4-trendmicro-maps/'
image: ''
---

I woke up one morning and got an email from a project manager. The original email from a client had a returned email with the following email server response:

_Remote server replied: 550 5.7.1 ... Mail from xxx.xxx.xxx.xxx blocked using Trend Micro [RBL][1] . Please see http://www.mail-abuse.com/cgi-bin/lookup?ip_address=xx.xxx.xxx.xxx_

We were black listed. So I went to their removal page, entered my [IP address][2] and waited. Later that day I get an email from them:

_xxx.xxx.xxx.xxx_ _is listed on the [DUL][3] because it is not defined in rDNS as static or dynamic. Upon checking, here is the rDNS:_

_xxx.xxx.xxx.xxx_ _(ec2-1__xxx.xxx.xxx.xxx__.compute-1.amazonaws.com)_

_You will need to work with your ISP to correctly define the IP, then ask them to contact us at_

_dul@mail-abuse.com_

_Then we can work with the ISP to resolve the issue and remove your IP._

They put the responsibility on Amazon to get the IP address de-listed, since they owned it. So after doing much research I found that this same problem had happened with

   [1]: http://en.wikipedia.org/wiki/DNSBL (DNSBL)
   [2]: http://en.wikipedia.org/wiki/IP_address (IP address)
   [3]: http://en.wikipedia.org/wiki/Dialup_Users_List (Dialup Users List)

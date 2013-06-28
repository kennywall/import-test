---
layout: post
title: Email in the Amazon Cloud Part 4 - TrendMicro Maps
url: http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-4-trendmicro-maps/
source: http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-4-trendmicro-maps/
domain: apievangelist.com
image: 
---
{% include JB/setup %}I woke up one morning and got an email from a project manager. The original email from a client had a returned email with the following email server response:
Remote server replied: 550 5.7.1 ... Mail from xxx.xxx.xxx.xxx blocked using Trend Micro RBL+. Please see http://www.mail-abuse.com/cgi-bin/lookup?ip_address=xx.xxx.xxx.xxx
We were black listed. So I went to their removal page, entered my IP address and waited. Later that day I get an email from them:
xxx.xxx.xxx.xxx is listed on the DUL because it is not defined in rDNS
as static or dynamic. Upon checking, here is the rDNS:
 xxx.xxx.xxx.xxx (ec2-1xxx.xxx.xxx.xxx.compute-1.amazonaws.com)
You will need to work with your ISP to correctly define the IP, then ask them to contact us at
dul@mail-abuse.com
Then we can work with the ISP to resolve the issue and remove your IP.

They put the responsibility on Amazon to get the IP address de-listed, since they owned it. So after doing much research I found that this same problem had happened with SpamHaus. Since so many spammers are also taking advantage of the cloud, top SPAM black lists were just blocking entire Amazon IP blocks. Not taking into considering the hundreds or thousands of valid Amazon Web Services customers sending email legitimately.
I can understand that spammers are a problem and that black lists have value in the SPAM game. However I viewed this as an attack on cloud computing. Everyone I talked to about the situation from TrendMicro to SAP IT in Germany all said the same thing. Why don't you just use a real infrastructure that isn't in the cloud. They just dismissed the cloud as the problem.
Trend Micro decided to just list the entire Amazon blocks rather than listing individual offenders.
So I needed to just wait for Amazon to do something or Trend Micro MAPS. So I just started lobbying both sides. Heavily!
They both pointed the finger at the other side. I escalated my ticket with Amazon Web Services and emailed Trend Micro MAPS on a daily basis asking them to not hold our business hostage any more.
Then I got a response on my Amazon Web Services support ticket one day about reverse DNS on our IP addresses.
Email in the Amazon Cloud - Part 1 - Part 2 - Part 3 - Part 4 - Part 5 - Part 6 - Guide  to Email in the Amazon Cloud

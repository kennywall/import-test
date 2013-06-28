---
layout: post
title: Amazon EC2 Recovery
url: http://apievangelist.com/2009/05/06/amazon-ec2-recovery/
source: http://apievangelist.com/2009/05/06/amazon-ec2-recovery/
domain: apievangelist.com
image: 
---
{% include JB/setup %}<p>I just finished a recovery of an amazon EC2 instance that failed. It failed not due to anything related to the Amazon EC2 instance. It was something Java related in the ColdFusion environment, and still trying to figure out.
Anwyays, as soon as I saw I couldn't recover the services necessary to run the application I quickly deployed a new instance from the AMI I had created of the production isntance a couple weeks ago.
Once up I copied all web site files. This frustrated me and took 25 minutes to copy because the D: always restores as empty drive with new instance. Gonna play with using volumes for production storage and see how this works.
Then I reinstalled certificates from backups.
Then we were backup and running. It wasn't a perfect process, but did it in about an hour.
Work to do to make perfect. And of course need to get the load-balancer working for this domain.</p>
<center><p><a href="http://apievangelist.com/2009/05/06/amazon-ec2-recovery/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

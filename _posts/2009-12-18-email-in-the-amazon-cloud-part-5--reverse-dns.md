---
layout: post
title: Email in the Amazon Cloud Part 5 - Reverse DNS
url: http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-5-reverse-dns/
source: http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-5-reverse-dns/
domain: apievangelist.com
image: 
---
{% include JB/setup %}<p>I was really excited when I got this email response on my ticket from Amazon Web Services:

We've reached out to the Amazon EC2 team and here are the next steps. In order for us to proceed, we'll need to setup DNS PTR records for EIPs (incl xxx.xxx.xxx.xxx) under your AWS account. Hence could you provide us with the names you would like to use and the corresponding EIPs (being used for email purposes)?
I believe the DNS PTR names should match the DNS 'A' records you may currently have resolving to these addresses. Provide us with the name you would like to use and we'll start the process on our end.

This was not the response I had expected. I thought either Amazon would negotiate a deal with Trend Micro MAPS to de-list their IP blocks and allow email to be sent or Trend Micro MAPS would back down from the pressure of everyone harassing them.
I really didn't think Amazon would start designating reverse DNS for their IP addresses. Even though this is the response that makes the most sense. I just thought they were too large to do this.
After some discussion and convincing of them that we were deserving of reverse DNS on 10 IP addresses I got it! I got an email telling me it was done. I did a reverse DNS lookup on all my reserved IP addresses and they reflected my core network domain.
I immediately approached Trend Micro MAPS and asked them one more time to de-list my IP addresses. They immediately responded and said it was done.
I found my faith in the cloud coming back.
Email in the Amazon Cloud - Part 1 - Part 2 - Part 3 - Part 4 - Part 5 - Part 6 - Guide  to Email in the Amazon Cloud
http://www.mail-abuse.com/
</p>
<center><p><a href="http://apievangelist.com/2009/12/18/email-in-the-amazon-cloud-part-5-reverse-dns/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

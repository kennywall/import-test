---
layout: post
title: "Email in the Amazon Cloud Part 5 - Reverse DNS"
url: 'http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-5-reverse-dns/'
image: ''
---

I was really excited when I got this email response on my ticket from [Amazon Web Services][1]:

_We've reached out to the Amazon EC2 team and here are the next steps. In order for us to proceed, we'll need to setup [DNS][2] [PTR][3] records for EIPs (incl_ _xxx.xxx.xxx.xxx__) under your AWS account. Hence could you provide us with the names you would like to use and the corresponding EIPs (being used for email purposes)?_

_I believe the DNS PTR names should match the DNS 'A' records you may currently have resolving to these addresses. Provide us with the name you would like to use and we'll start the process on our end._

This was not the response I had expected. I thought either Amazon would negotiate a deal with [Trend Micro MAPS][4] to de-list their IP blocks and allow email to be sent or [Trend Micro MAPS][4] would back down from the pressure of everyone harassing them.

I really didn't think Amazon would start designating reverse DNS for their [IP addresses][5]. Even though this is the response that makes the most sense. I just thought they were too large to do this.

After some discussion and convincing of them that we were deserving of reverse DNS on 10 IP addresses I got it! I got an email telling me it was done. I did a [reverse DNS lookup][6] on all my reserved IP addresses and they reflected my core network domain.

I immediately approached [Trend Micro MAPS][4] and asked them one more time to de-list my IP addresses. They immediately responded and said it was done.

I found my [faith in the cloud][7] coming back.

**Email in the Amazon Cloud** \- [Part 1][8] \- [Part 2][9] \- [Part 3][10] \- [Part 4][11] \- [Part 5][12] \- [Part 6][7] \- [Guide to Email in the Amazon Cloud][13]



   [1]: http://aws.amazon.com/
   [2]: http://en.wikipedia.org/wiki/Domain_Name_System (Domain Name System)
   [3]: http://finance.yahoo.com/q?s=PTR (NYSE: PTR)
   [4]: http://www.mail-abuse.com/
   [5]: http://en.wikipedia.org/wiki/IP_address (IP address)
   [6]: http://en.wikipedia.org/wiki/Reverse_DNS_lookup (Reverse DNS lookup)
   [7]: http://www.kinlane.com/?p=1106
   [8]: http://www.kinlane.com/?p=1095
   [9]: http://www.kinlane.com/?p=1098
   [10]: http://www.kinlane.com/?p=1100
   [11]: http://www.kinlane.com/?p=1102
   [12]: http://www.kinlane.com/?p=1104
   [13]: http://www.kinlane.com/2010/07/email-infrastructure-in-the-amazon-cloud/

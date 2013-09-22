---
layout: post
title: "Email in the Amazon Cloud Part 3 - Maintaining IP Addresses and DNS Quality"
url: 'http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-3-maintaining-ip-addresses-and-dns-quality/'
image: ''
---

Sending large amounts of email and ensuring they get received requires a lot of work and you need to make sure your mail framework is setup correctly and is healthy. This takes a lot of work and maintenance.

First off I reserve 11 [IP addresses][1] with [Amazon Web Services][2]. I reserve these 11 IP addresses and never let them back into the general pool.

I setup [DNS][3] for my domain to reflect using 10 of the IP addresses as smtp1.mydomain.com through smtp10.mydomain.com and properly setup [MX records][4] accordingly.

Now [reverse DNS][5] on IP addresses is nice, but in my experience is not mission critical for sending email. All last year we were fine, I sent probably 10-20 large email blasts using this setup, with no major problems with emails being received.

Before doing any emailing I check all my IP addresses against major blacklists to see if we've been listed. We have been listed on blacklists before and easily was able to get removed with no problem.

Then in November we encountered [Trend Micro MAPS][6].

**Email in the Amazon Cloud** \- [Part 1][7] \- [Part 2][8] \- [Part 3][9] \- [Part 4][10] \- [Part 5][11] \- [Part 6][12] \- [Guide to Email in the Amazon Cloud][13]

   [1]: http://en.wikipedia.org/wiki/IP_address (IP address)
   [2]: http://aws.amazon.com/
   [3]: http://en.wikipedia.org/wiki/Domain_Name_System (Domain Name System)
   [4]: http://en.wikipedia.org/wiki/MX_record (MX record)
   [5]: http://en.wikipedia.org/wiki/Reverse_DNS_lookup (Reverse DNS lookup)
   [6]: http://www.kinlane.com/?p=1102
   [7]: ../?p=1095
   [8]: ../?p=1098
   [9]: ../?p=1100
   [10]: ../?p=1102
   [11]: ../?p=1104
   [12]: ../?p=1106
   [13]: ../2010/07/email-infrastructure-in-the-amazon-cloud/

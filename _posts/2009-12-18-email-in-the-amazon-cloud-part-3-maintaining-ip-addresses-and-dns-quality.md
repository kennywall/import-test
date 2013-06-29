---
layout: post
title: Email in the Amazon Cloud Part 3 Maintaining IP Addresses and DNS Quality
url: http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-3-maintaining-ip-addresses-and-dns-quality/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
Sending large amounts of email and ensuring they get received requires a lot of work and you need to make sure your mail framework is setup correctly and is healthy. This takes a lot of work and maintenance.
First off I reserve 11 IP addresses with Amazon Web Services. I reserve these 11 IP addresses and never let them back into the general pool.
I setup DNS for my domain to reflect using 10 of the IP addresses as smtp1.mydomain.com through smtp10.mydomain.com and properly setup MX records accordingly.
Now reverse DNS on IP addresses is nice, but in my experience is not mission critical for sending email. All last year we were fine, I sent probably 10-20 large email blasts using this setup, with no major problems with emails being received.
Before doing any emailing I check all my IP addresses against major blacklists to see if we've been listed. We have been listed on blacklists before and easily was able to get removed with no problem.
Then in November we encountered Trend Micro MAPS.
Email in the Amazon Cloud - Part 1 - Part 2 - Part 3 - Part 4 - Part 5 - Part 6 - Guide  to Email in the Amazon Cloud

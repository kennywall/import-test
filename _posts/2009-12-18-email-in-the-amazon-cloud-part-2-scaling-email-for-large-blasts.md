---
layout: post
title: Email in the Amazon Cloud Part 2 Scaling Email for Large Blasts
url: http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-2-scaling-email-for-large-blasts/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}

In the past we would send emails and then sit and watch servers for 24-72 hours, with constant server restarts and other problems.
I came up with a new base configuration that involved using a single blast server for queuing up and sending the personalized emails. This blast server would alternate between several SMTP servers to balance the load and increase the volume at which we could send the emails out.
I ran some tests and to achieve the results I wanted it required an SMTP server per 50K emails. I could guarantee emails would go out in about 4-6 hours with remaining trickling out over the next 24 hours.
So for a 500k email blast I would fire up an x-large blast instance and 10 large SMTP instances using Amazon EC2. I had all the log files for the SMTP servers writing to a common EBS volume that I could maintain the records even after I shut down the instances.
I was getting closer to being ready for business. I need to make sure the IP addresses and DNS infrastructure for the email blasts was 100% next.
Email in the Amazon Cloud - Part 1 - Part 2 - Part 3 - Part 4 - Part 5 - Part 6 - Guide  to Email in the Amazon Cloud
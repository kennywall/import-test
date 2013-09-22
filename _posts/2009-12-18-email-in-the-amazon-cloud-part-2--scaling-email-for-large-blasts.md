---
layout: post
title: "Email in the Amazon Cloud Part 2 - Scaling Email for Large Blasts"
url: 'http://kinlane.com/2009/12/18/email-in-the-amazon-cloud-part-2-scaling-email-for-large-blasts/'
image: ''
---

I needed to send a large amounts of email. We are talking 500,000 to 1 million emails in each send. These are emails being sent to encourage event attendance or interaction, so they need to go out quickly. The powers that be wanted to have emails go out in 24 hours.

In the past we would send emails and then sit and watch servers for 24-72 hours, with constant server restarts and other problems.

I came up with a new base configuration that involved using a single blast server for queuing up and sending the personalized emails. This blast server would alternate between several SMTP servers to balance the load and increase the volume at which we could send the emails out.

I ran some tests and to achieve the results I wanted it required an SMTP server per 50K emails. I could guarantee emails would go out in about 4-6 hours with remaining trickling out over the next 24 hours.

So for a 500k email blast I would fire up an x-large blast instance and 10 large SMTP instances using [Amazon EC2][1]. I had all the log files for the SMTP servers writing to a common EBS volume that I could maintain the records even after I shut down the instances.

I was getting closer to being ready for business. I need to make sure the [IP addresses and DNS infrastructure for the email][2] blasts was 100% next.

**Email in the Amazon Cloud** \- [Part 1][3] \- [Part 2][4] \- [Part 3][5] \- [Part 4][6] \- [Part 5][7] \- [Part 6][8] \- [Guide to Email in the Amazon Cloud][9]

   [1]: http://aws.amazon.com/ec2/
   [2]: http://www.kinlane.com/?p=1100
   [3]: ../?p=1095
   [4]: ../?p=1098
   [5]: ../?p=1100
   [6]: ../?p=1102
   [7]: ../?p=1104
   [8]: ../?p=1106
   [9]: ../2010/07/email-infrastructure-in-the-amazon-cloud/

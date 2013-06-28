---
layout: post
title: Running Your Event in the Cloud - Email
url: http://apievangelist.com/2010/06/09/running-your-event-in-the-cloud-email/
source: http://apievangelist.com/2010/06/09/running-your-event-in-the-cloud-email/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/events-in-the-clouds/email_icon.jpg
---
{% include JB/setup %}<p>Email is still the number one tool for managing events and communicating  with attendees, speakers, and exhibitors. Social network is definitely  the future of the event communication, but until then email rules.
Sending  out call for papers, speaker, exhibitor, attendee invitations and other  emails around a conference can require a well oiled email  infrastructure to make sure emails get into the inbox.
I see  events send anywhere from a few hundred to several million emails over  the life span of an event. Sending emails in the cloud can work well  whether your sending a small amount using Google Apps or millions using  Amazon Web Services.

	Google Apps is a quick way for events to  setup email at their domain and not worry about email delivery, receipt  and SPAM. It has a 500 daily limit on how much you can send, but works  well for smaller events.
	Amazon Web Services provides even more  industrial strength when it comes to larger events and conferences

Amazon  provides the necessary computing power to get emails out the door  efficiently. Now that Amazon allows for reverse DNS on reserved IP  addresses it makes Amazon a viable solution for permanent and temporary  email infrastructure.
I often scale primary email infrastructure  from 1 POP / SMTP server to 3 during an event to support ongoing daily  emails. I also will scale up to 10 SMTP servers for 24 hour periods to  support large scale email blasts.
Amazon EC2 is the computing  power, and Amazon S3 is great storage for emails, logs, and more. With a  proper plan strategy, email in the clouds is possible.</p>
<center><p><a href="http://apievangelist.com/2010/06/09/running-your-event-in-the-cloud-email/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

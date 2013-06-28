---
layout: post
title: Cloud Balancing with Global Server Load Balancer (GSLB)
url: http://apievangelist.com/2010/07/08/cloud-balancing-with-global-server-load-balancer-gslb/
source: http://apievangelist.com/2010/07/08/cloud-balancing-with-global-server-load-balancer-gslb/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/cloud-computing/Global-Load-Balancing.PNG
---
{% include JB/setup %}<p>Last year I moved web site, database and email services for the SAP SAPPHIRE event to the Amazon Cloud. We needed to scale our infrastructure dramatically to support the event for about 4 months out of the year. This was our second year running the conference in the Amazon Cloud and we were able to scale up nicely to handle the traffic. There were still issues. 
Global Traffic and Latency
We ran systems to support SAPPHIRE Frankfurt as well as the Virtual SAPPHIRE. So our traffic was from all over the world, and specifically in Europe for a large portion. Availability and latency with various web applications become critical. I am research different methods for addressing not only for SAPPHIRE next year but a year round calendar of events for SAP, Google and other clients.
I'm researching DNS-based Global Server Load Balancing or GSLB solutions such as Dynect. GSLB allows you to distribute application load between data centers or cloud providers in any zone or global region you choose. Traffic can be routed based upon:

	User Geography
	Server Capacity / Availability
	Geographic Based Laws and Regulation

Based upon a users location when they load my application at registration.eventdomain.com and they are located in Europe, using DNS I can route them to registration-eu.domain.com which is routed to server instances I have deployed in Europe using Amazon EC2. Using Global Server Load Balancing I can:

	Balance server traffic more evenly across my cloud infrastructure
	Create a better user experience by routing them to servers closest to them.
	Avoid Internet outages and bottle necks

Overall this will increase application performance and better meet business objectives around delivery web applications to users. As I"m supporting events and conferences in more locations around the world, this type of web application delivery using Infrastructure as a Services (IaaS) and Global Server Load Balancing (GLSB) is becoming critical.
Update:  I am also researching Zeus as part of our Global Server Load Balancer strategy, and they were so kind to let us use their image.</p>
<center><p><a href="http://apievangelist.com/2010/07/08/cloud-balancing-with-global-server-load-balancer-gslb/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

---
layout: post
title: "Cloud Balancing with Global Server Load Balancer (GSLB)"
url: 'http://kinlane.com/2010/07/08/cloud-balancing-with-global-server-load-balancer-gslb/'
image: 'http://kinlane-productions.s3.amazonaws.com/cloud-computing/Global-Load-Balancing.PNG'
---

Last year I moved web site, database and email services for the [SAP SAPPHIRE][1] event to the Amazon Cloud. We needed to scale our infrastructure dramatically to support the event for about 4 months out of the year. This was our second year running the conference in the Amazon Cloud and we were able to scale up nicely to handle the traffic. There were still issues. [<img class="alignnone c1" title="Global Server Load Balancing" src="http://kinlane-productions.s3.amazonaws.com/cloud-computing/Global-Load-Balancing.PNG" alt="" width="286" height="192" align="right" />][2]

**Global Traffic and Latency**

We ran systems to support SAPPHIRE Frankfurt as well as the [Virtual SAPPHIRE][3]. So our traffic was from all over the world, and specifically in Europe for a large portion. Availability and latency with various web applications become critical. I am research different methods for addressing not only for SAPPHIRE next year but a year round calendar of events for SAP, Google and other clients.

I'm researching DNS-based Global Server Load Balancing or GSLB solutions such as [Dynect][4]. GSLB allows you to distribute application load between data centers or cloud providers in any zone or global region you choose. Traffic can be routed based upon:

  * User Geography
  * Server Capacity / Availability
  * Geographic Based Laws and Regulation
Based upon a users location when they load my application at _**registration.eventdomain.com**_ and they are located in Europe, using [DNS][5] I can route them to registration-eu.domain.com which is routed to server instances I have deployed in Europe using Amazon EC2. Using Global Server Load Balancing I can:

  * Balance server traffic more evenly across my cloud infrastructure
  * Create a better user experience by routing them to servers closest to them.
  * Avoid Internet outages and bottle necks
Overall this will increase application performance and better meet business objectives around delivery web applications to users. As I"m supporting events and conferences in more locations around the world, this type of web application delivery using [Infrastructure as a Services][6] (IaaS) and Global Server Load Balancing (GLSB) is becoming critical.

**Update:** I am also researching [Zeus][2] as part of our [Global Server Load Balancer strategy][2], and they were so kind to let us use their image.

   [1]: https://www.sapandasug.com/
   [2]: http://www.zeus.com/
   [3]: http://www.sapphirenow.com/
   [4]: http://dyn.com/dynect
   [5]: http://www.kinlane.com/category/dns/
   [6]: http://www.kinlane.com/category/infrastructure-as-a-service-iaas/

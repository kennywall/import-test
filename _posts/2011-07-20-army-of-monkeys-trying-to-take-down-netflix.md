---
layout: post
title: Army of Monkeys Trying to Take Down Netflix
url: http://apievangelist.com/2011/07/20/army-of-monkeys-trying-to-take-down-netflix/
source: http://apievangelist.com/2011/07/20/army-of-monkeys-trying-to-take-down-netflix/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/Evil_Monkey.gif
---
{% include JB/setup %}<p>Netflix wrote an interesting post about making their systems, redundant and more fault-tolerant, while running in the Clouds. Since no single component in the cloud can guarantee 100% up-time, Netflix has to design a cloud architecture where individual components can fail without affecting the availability of the entire system.
To do this, Netflix uses techniques like graceful degradation on dependency failures, as well as node-, rack-, datacenter/availability-zone and even regionally-redundant deployments. However, designing a fault tolerant architecture is not enough, they have to be able to regularly test and know if they can survive any outage.
So Netflix built Chaos Monkey, a tool that randomly disables their production instances, to make sure Netflix can survive this common type of failure without any customer impact. Neflix runs this during regular business hours in a very controlled way, to learn about how their network responds, as they work to make it more resilient.
Inspired by the success of the Chaos Monkey, they've started creating a whole new line of simians that induce various kinds of failures, or detect abnormal conditions, and test our ability to survive them:

	Latency Monkey - Induces artificial delays in the NEtflix RESTful client-server communication layer to simulate service degradation.
	Conformity Monkey - Discovers instances that don't adhere to best-practices and shuts them down.
	Doctor Monkey - Taps into health checks that run on each instance as well as monitors other external signs of health to detect unhealthy instances.
	Janitor Monkey - Ensures that the Netflix cloud environment is running free of clutter and waste, by searching for unused resources and disposing of them.
	Security Monkey - An extension of Conformity Monkey. It finds security violations or vulnerabilities, such as improperly configured AWS security groups, and terminates the offending instances.
	10-18 Monkey - Detects configuration and run time problems in instances serving customers in multiple geographic regions, using different languages and character sets.
	Chaos Gorilla - Similar to Chaos Monkey, but simulates an outage of an entire Amazon availability zone.

As Netflix grows at an unprecendented pace, testing for all types of failure scenarios will be anever-endingjob. They are in some seriously uncharted territory, with the number of instances they run and bandwidth they consume, while running completely in the Amazon cloud.
The Netflix simian army can be a model for cloud fault tolerance, that the rest of us can learn from. Let's just hope the Netflix simian army never develops a mind of its and comes after the rest of us.
</p>
<center><p><a href="http://apievangelist.com/2011/07/20/army-of-monkeys-trying-to-take-down-netflix/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

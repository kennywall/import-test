---
layout: post
title: Army of Monkeys Trying to Take Down Netflix
url: http://apievangelist.com/2011/07/20/army-of-monkeys-trying-to-take-down-netflix/
source: http://apievangelist.com/2011/07/20/army-of-monkeys-trying-to-take-down-netflix/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/Evil_Monkey.gif
---
{% include JB/setup %}<p>Netflix wrote an interesting post about making their systems, redundant and more fault-tolerant, while running in the Clouds.Since no single component in the cloud can guarantee 100% up-time, Netflix has to design a cloud architecture where individual components can fail without affecting the availability of the entire system.To do this, Netflix uses techniques like graceful degradation on dependency failures, as well as node-, rack-, datacenter/availability-zone and even regionally-redundant deployments.However, designing a fault tolerant architecture is not enough, they have to be able to regularly test and know if they can survive any outage.So Netflix built Chaos Monkey, a tool that randomly disables their production instances, to make sure Netflix can survive this common type of failure without any customer impact.</p>
<center><p><a href="http://apievangelist.com/2011/07/20/army-of-monkeys-trying-to-take-down-netflix/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

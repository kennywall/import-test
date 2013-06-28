---
layout: post
title: Distributed Data and Syndication
url: http://apievangelist.com/2008/05/30/distributed-data-and-syndication/
source: http://apievangelist.com/2008/05/30/distributed-data-and-syndication/
domain: apievangelist.com
image: 
---
{% include JB/setup %}<p>I am building out a pretty complex system that really seems like a lot of overhead to get some pretty basic systems up.It involves republishing small subsets of data to various data stores such as MySQL, Amazon S3, GData, or just XML.Then I syndicate web services / feeds in RSS, XML, JSON to those little data stores.I keep getting asked why don't you just allow one central data feed off main data store.From a security and load balancing standpoint the distributed piece just makes sense.  It allows me to publish on a schedule these small data stores for each partner / client.   I can give them access directly to the raw data as well as the feed.Also the feed and data can scale and grow independently of the central data store.  It really helps me to scale data feeds and each partners needs.Alright....just jotting down these thoughts in case I change them..</p>
<center><p><a href="http://apievangelist.com/2008/05/30/distributed-data-and-syndication/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

---
layout: post
title: "What Really Caused the Amazon Web Services Outage?"
url: 'http://kinlane.com/2011/04/29/what-really-caused-the-amazon-web-services-outage/'
image: 'http://kinlane-productions.s3.amazonaws.com/matrix-pics/blue-matrix-400.jpg'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/matrix-pics/blue-matrix-400.jpg" alt="" width="300" align="right" />Amazon released a summary of the [Amazon EC2 and Amazon RDS service disruption in the US East Region][1] today.

These so caled stuck volumes and stuck EC2 instances, well those were mine.

Right after midnight on April 21st I was working on one of my harvest tools, which pulls feeds from all major blogs, breaks them down and stores them for analysis.

I was reviewing the analysis for what it pulled in the last hour, then my EC2 instance froze. I closed everything down and logged back into the root, but it took be about 45 minutes to actually get things to load back up.

Once back in I saw some sort of scan going on? Whatever was scanning on this instance was going through large volumes of information, and it was moving so fast I really couldn't make sense of it.

I tried to shut things down, but couldn't. I'd lost control over my instance. I run a quadruple extra large instance for harvesting data. For nearly 4 days I couldn't get my machine to respond.

I assumed once Amazon resolved their problems, then I could get back in.

It was late Sunday night before I was able to get back into my instance, everything looked fine. Upon closer inspection I noticed that my hard drive was all but maxed out. I started looking further and noticed my normally 500 GB EBS volume was now 1 TB. Then I noticed there were 25 separate 1TB EBS volumes attached. Holy shit, where did this come from?

I started going through these drives, they appeared to full of logs of the last 4 days activities.

I was curious to know what happened, so I started looking through. I started with the files timestamped from 4/21/2011.

The logs contained complete copies of everything I've harvested over the last years, but that was just the first 4 hours. After that it looks like some other data, I do not recognize it.

After looking for patterns I noticed several things. In the first 2 hours I saw my dictionary database I use for indexing harvested data processed, with following coded tags around each word:

_112 114 111 99 101 115 115_

   [1]: http://aws.amazon.com/message/65648/

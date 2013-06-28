---
layout: post
title: Not All Browsers Are the Same
url: http://apievangelist.com/2009/02/27/not-all-browsers-are-the-same/
source: http://apievangelist.com/2009/02/27/not-all-browsers-are-the-same/
domain: apievangelist.com
image: 
---
{% include JB/setup %}As part of my 3rd party service development plan for my company I make recommendations for external systems that my company should be using for its operations. We don't buy or develop everything internally. There are some amazing 3rd party applications.
A couple notable ones are:

	Gmail / Google Apps for Your Domain
	Google Docs
	Google Calendar
	Email Center Pro (ECP)

These are applications that I have integrated heavily into our daily operations. Another characteristic they all have is they are heavy JavaScript based applications. One thing I started noticing is my non-tech savvy employees tend to leave these programs open and running all day long. And many will leave their browser open for multiple days with the same application open.
Most users are using IE, but a few use Firefox. Memory leaks become a major problem. People's machines slow to a crawl and many times just lock up. I can people complaining and worried applications or their machines.
So I started recommending using Google Chrome for their web-based JavaScript application. In initial tests I opened Gmail Personal, Google Docs Personal, Gmail for Google Apps, Google Docs for Apps, and Email Center Pro in both Chrome and Firefox.
I left these open all night:

	Firefox started at about 50K and grew to 480K by morning.
	Chrome started at about 50K and reduced to 46K by morning.

All without usage? I am leaving open all day to see what happens next.
---
layout: post
title: Google Reader API
url: http://kinlane.com/2011/09/13/google-reader-api/
image: http://kinlane-productions.s3.amazonaws.com/google/google-reader.jpg
---
{% include JB/setup %}
One thing I love about Google, is the APIs. The apps I use most like Gmail, Calendar and Docs all have APIs, allowing me to write code that works my accounts and its data, and integrate it into other applications.
Well except for one application, Google Reader. Google has never made an API for Google Reader. It onlyallowsyou to use RSS feeds and sharing them publicly. I've always wanted to get at thewealthof knowledge that is curated daily in my Google Reader.
So I tend to look regularly to see if they have put one out. Tonight I came across a Google Code project that says it:
Hosts documentation and the issue tracker for the (unofficial) Google Reader API.
It has a Googler working on it, that was from the reader team. It appears to be work in progress, but has activity in the last month.
Here are the pages currently up:

	ApiSubscriptionEdit - Allows a stream to be subscribed to, unsubscribed from, or an existing subscription to be edited.
	StreamId - Description of stream IDs exposed by the Google Reader API. "Streams" refer to collections of items in the Google Reader API. This includes feeds, items with a specific tag, or folders. Stream IDs are are string-based identifiers used to identify streams and are passed to many API methods.
	ItemId - Description of item IDs exposed by the Google Reader API. Items in Reader are referenced by globally unique item IDs. IDs are generally derived from the &lt;id&gt; attribute in Atom feeds and the &lt;guid&gt; attribute in RSS feeds. In the absence of those, the item URL may be used to generat the ID. In cases where the feed does not provide IDs or URLs (or they are not deemed "trustworthy", e.g. if more than one item in the feed response has the same ID or URL), then the ID will be computed from a signature of certain feed item properties (title, body, etc.).
	ApiStreamItemsIds - Given one or more StreamIds and fetching options, returns the IDs of the items in those Streams. Getting just item IDs is significantly cheaper than getting stream contents. If you need to do filtering of items, it is highly encouraged to do this at the ID level before fetching item contents for the subset of items that remain.
	ApiStreamItemsContents - Given a collection of ItemIds and fetching options, returns the contents of those items.
	ApiCommonInputs - Inputs that all API methods support
	ActionToken - Describes XSRF-preventing action tokens.
	ApiStreamContents - Given a StreamId and fetching options, returns the contents of the items in that Stream.
	Authentication - Making authenticated requests with OAuth and ClientLogin

I'm going to make some time this weekend to play with more and write some code. I would like to rework my tagging system in Google Reader and drive information for sites that run in my new content management system.
I'm excited to finally see a potential API for Google Reader, and the possibility that they are not going to abandon one of my favorite tools.
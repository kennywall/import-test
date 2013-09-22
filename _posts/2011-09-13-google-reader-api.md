---
layout: post
title: "Google Reader API"
url: 'http://kinlane.com/2011/09/13/google-reader-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/google/google-reader.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google/google-reader.jpg" alt="" width="290" align="right" />][1]One thing I love about Google, is the APIs. The apps I use most like Gmail, Calendar and Docs all have APIs, allowing me to write code that works my accounts and its data, and integrate it into other applications.

Well except for one application, [Google Reader][1]. Google has never made an API for Google Reader. It onlyallowsyou to use RSS feeds and sharing them publicly. I've always wanted to get at thewealthof knowledge that is curated daily in my Google Reader.

So I tend to look regularly to see if they have put one out. Tonight I came across a [Google Code project][2] that says it:

_Hosts documentation and the issue tracker for the (unofficial) Google Reader API._ It has a [Googler working on it][3], that was from the reader team. It appears to be work in progress, but has activity in the last month.

Here are the pages currently up:

  * **[ApiSubscriptionEdit][4]** \- Allows a stream to be subscribed to, unsubscribed from, or an existing subscription to be edited.
  * **[StreamId][5]** \- Description of stream IDs exposed by the Google Reader API. "Streams" refer to collections of items in the Google Reader API. This includes feeds, items with a specific tag, or folders. Stream IDs are are string-based identifiers used to identify streams and are passed to many API methods.
  * **[ItemId][6]** \- Description of item IDs exposed by the Google Reader API. Items in Reader are referenced by globally unique item IDs. IDs are generally derived from the

   [1]: http://www.google.com/reader
   [2]: http://code.google.com/p/google-reader-api/
   [3]: https://plus.google.com/111567061469336027617/posts
   [4]: http://code.google.com/p/google-reader-api/wiki/ApiSubscriptionEdit
   [5]: http://code.google.com/p/google-reader-api/wiki/StreamId
   [6]: http://code.google.com/p/google-reader-api/wiki/ItemId

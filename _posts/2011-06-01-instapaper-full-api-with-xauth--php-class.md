---
layout: post
title: "Instapaper Full API with XAuth - PHP Class"
url: 'http://kinlane.com/2011/06/01/instapaper-full-api-with-xauth-php-class/'
image: 'http://kinlane-productions.s3.amazonaws.com/instapaper.png'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/instapaper.png" alt="" width="175" align="right" />][1]I'm working my way through a list of projects I have, and currently the[Instapaper API][1] is top of my list.

I couldn't find an easy to use PHP class for authenticating against Instapaper's Full API using XAuth.

So I downloaded [@abraham][2] [Twitter OAuth][3] and stripped out all as much of theunnecessarypieces as I could.

I was quickly able to get it up and running authenticating with Instapaper's Full API using[XAuth][4].

I added two basic methods for:

  * Listing Instapaper Bookmarks
  * Pulling Full Text of Instapaper Bookmark
I will add more methods later for other Instapaper API endpoints.

One thing you need to know is this is only for full READ / WRITE on the Instapaper API. If you just want to add bookmarks this is not for you, just use the [simple API][5].

I'm moving to extend this class for [printing read it later binders][6] for research and other areas, then I'll come back and add more to this repository.

You can [download / checkout on Github][7].

######  Related articles

  * [Instapaper and the Concept of Monetizing Your API][8] (programmableweb.com)
  * [Read It Later Binder Using Instapaper][9] (kinlane.com)
  * [Instapaper Mobile App and API Strategy][10] (apievangelist.com)

   [1]: http://www.instapaper.com/api/full (Instapaper API)
   [2]: http://twitter.com/#!/abraham (@abraham)
   [3]: https://github.com/abraham/twitteroauth (Twitter OAuth)
   [4]: http://xauth.org/ (XAuth)
   [5]: http://www.instapaper.com/api/simple (simple API)
   [6]: http://developer.mimeo.com/projects/idea_detail.php?ID=13 (printing read it later binders)
   [7]: https://github.com/kinlane/InstapaperXAuth (download / checkout on Github)
   [8]: http://blog.programmableweb.com/2011/04/07/instapaper-and-the-concept-of-monetizing-your-api/
   [9]: http://www.kinlane.com/2011/05/read-it-later-binder-using-instapaper/
   [10]: http://blog.apievangelist.com/2011/04/28/instapaper-mobile-app-and-api-strategy/

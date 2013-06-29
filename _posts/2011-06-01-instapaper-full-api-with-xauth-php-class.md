---
layout: post
title: Instapaper Full API with XAuth PHP Class
url: http://kinlane.com/2011/06/01/instapaper-full-api-with-xauth-php-class/
image: http://kinlane-productions.s3.amazonaws.com/instapaper.png
---
{% include JB/setup %}
<p>
     I'm working my way through a list of projects I have, and currently theInstapaper API is top of my list. I couldn't find an easy to use PHP class for authenticating against Instapaper's Full API using XAuth. So I downloaded @abraham Twitter OAuth and stripped out all as much of theunnecessarypieces as I could. I was quickly able to get it up and running authenticating with Instapaper's Full API usingXAuth. I added two basic methods for: Listing Instapaper Bookmarks Pulling Full Text of Instapaper Bookmark I will add more methods later for other Instapaper API endpoints. One thing you need to know is this is only for full READ / WRITE on the Instapaper API. If you just want to add bookmarks this is not for you, just use the simple API. I'm moving to extend this class for printing read it later binders for research and other areas, then I'll come back and add more to this repository. You can download / checkout on Github. Related articles Instapaper and the Concept of Monetizing Your API (programmableweb.com) Read It Later Binder Using Instapaper (kinlane.com) Instapaper Mobile App and API Strategy (apievangelist.com)
</p>
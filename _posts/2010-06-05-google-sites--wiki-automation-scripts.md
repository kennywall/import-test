---
layout: post
title: "Google Sites / Wiki Automation Scripts"
url: 'http://kinlane.com/2010/06/05/google-sites-wiki-management-scripts/'
image: 'http://code.google.com/apis/sites/images/gdata-sites-150.png'
---

Having fun playing with [Google Sites API][1] today. Audrey is setting up Wikis for different research areas to support her new [Hack Education][2] site. I am reviving my [cloud computing research wiki][3]. I am looking for new ways to keep sections of the wiki alive programatically. A couple ways I've brainstormed:<img class="alignnone c1" title="Google Sites" src="http://code.google.com/apis/sites/images/gdata-sites-150.png" alt="" width="150" height="150" align="right" />

  * **Links Page** \- Automatically update a page with links. Links would be pulled hourly from a [Delicious][4] account, or any other social bookmarking site with RSS feed or API. It would auto generate the page with all links alphabetically. It could either link directly to the URL of the bookmark or create a static page with title of link and add Title, Description, Tags and URL to the static wiki page on Google Sites.
  * **Blog Section** \- Automatically pull the RSS feed from a desired blog or set of blogs and pull / update every hour and when new blog entry is found it adds to master list and creates a detail page for that blog. Then it would publish the blog entry to the static page with Title, Body, Tags, etc.
  * **Image Gallery** \- Automatically update an image gallery page / section. Images would be pulled hourly from a [Flickr][5] account, or any other image sharing site with RSS feed or API. It would auto generate the page with all images with thumbnail and title sorted by popularity on the Google Sites page. It would then create a static page with image title and full size image, Title, Description, Tags and URL to the page on [Google Sites][6].
These are just a couple of quick ideas for **Google Site Automation Scripts** that could be created using [Google Sites API][1] to help make [Google Site / Wiki][6] management easier.

   [1]: http://code.google.com/apis/sites/
   [2]: http://www.hackeducation.com/
   [3]: http://cloud.kinlane.com
   [4]: http://delicious.com/
   [5]: http://www.flickr.com
   [6]: http://sites.google.com

---
layout: post
title: "Local Places Data Using CityGrid with Hyp3rL0cal"
url: 'http://kinlane.com/2011/12/18/local-places-data-using-citygrid-with-hyp3rl0cal/'
image: 'http://kinlane-productions.s3.amazonaws.com/citygrid/citygrid_logo.jpg'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/citygrid/citygrid_logo.jpg" alt="" width="250" align="right" />][1]I needed to learn more about the[CityGrid APIs][1]. What better way than to actually build a prototype.

I thought it would be good to have a [simple local business directory][2] that could be deployed all by itself, or as part of another web site.

I wanted the directory to look good, but I didn't want to do any graphic design, so I used[Twitter Bootstrap][3]for the user interface (UI).

I put together five pages, allowing you to browse some local business categories in West Hollywood, CA.[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/hyp3rl0cal/Hyp3rL0cal-3.png" alt="" width="350" align="right" />][4]

  * Home
  * About
  * Search
  * Detail
  * Contact
The site doesn't use a database. You set the sites config file to a city and state, it makes calls to the[CityGrid APIs][1]in real-ime, with the latest business listings, images, offers and reviews.

The site is providing a way for me to learn about the [CityGrid APIs][1], while also producing usable code that other developers can use to bootstrap their own hyperlocal sites and applications.

This project is still in development, you can[download it at Github][5].

I will work on other enhancements to this prototype, but first I'd like to create a ruby and python version of Hyp3rl0cal, so it can be used as a base for CityGrid API development.

Lot's of learning ahead, I will keep publishing my code to Github and link everything at [Hyp3rL0cal][4].

 

   [1]: http://developer.citygridmedia.com/ (CityGrid APIs)
   [2]: http://hyp3rl0cal.com/index.php (simple local business directory)
   [3]: http://twitter.github.com/bootstrap/
   [4]: http://hyp3rl0cal.com/ (Hyp3rL0cal)
   [5]: https://github.com/kinlane/CityGrid---Local-Directory

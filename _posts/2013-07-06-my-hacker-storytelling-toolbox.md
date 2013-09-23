---
layout: post
title: "My Hacker Storytelling Toolbox"
url: 'http://kinlane.com/2013/07/06/hacker-storytelling-toolbox/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/bw-toolbox.jpg'
---

[<img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-toolbox.jpg" alt="" width="250" align="right" />][1]

I'm working with a variety of tools and services to keep up with my daily research, curation, analysis and ultimately publishing of stories from the world of APIs.

Over the last six months I've migrated to an approach I've called [Hacker Storytelling][2]. My goal is to efficiently discover, organize and publish as many meaningful stories around the best practices in the business of APIs, as I can, while encouraging the widest possible distribution as I can.

Hacker Storytelling currently centers around publishing of micro project sites as Github repositories using a simple, blog-aware, static site generator called [Jekyll][3]. You can do a lot of storytelling with static markup or markdown via pages and chronological blog posts.

Even with pages and blogs, I need more fuel for my stories. I use [Mustache][4] [JSON][5] to display everything from simple bulleted or numbered lists, t company and tool listings. Mustache allows me to maintain a central data store, which I use as efficiently as I can across all the stories I tell.

To help me acquire this data, [I depend on multiple APIs][6], but when it comes down to it, a lot of my data is harvested or scraped. To manage my harvesting I use [ScraperWiki][7], to acquire, cleanup and deliver in a structured data in a JSON format. I maintain a vast archive of data as JSON files, across multiple Github repositories where I use [JSON Editor Online][8] to edit in a quick and dirty way. Adding the essential, human element to my curation algorithm.

In addition to my projects, I do a lot of speaking. I have a standard approach to [publishing content from my central content and data stores as presentations][9]. Each conference keynote or session I do, as well as presentations for meet ups, hackathons or even internally at various companies is centered around a presentation i custom build at the moemnt of delivery. I use either [deck.js][10] or [reveal.js][11] for my presentation delivery tool, as opposed to a classic Powerpoint or newer Google Presentation.

Once I create static pages, blog posts and presentations using content and data I've curated and written, I need a place to put it. I usually start with a [Github][12] repository, using Git as the central project management platform. After that, if I want a project to have a public life, I will publish to the web using [Github Pages][13], [Amazon S3][14] or [Dropbox][15], depending on my goals around the project.

You can find a list of services and tools I'm currently using on the [Hacker Storytelling Toolbox][1] page. I will keep it up to date as I find new tools and services. If there is anything you think I should consider, that contributes to your own storytelling process, please let me know.

   [1]: http://hackerstorytelling.com/toolbox.html (Hacker Storytelling Toolbox)
   [2]: http://hackerstorytelling.com (Hacker Storytelling)
   [3]: http://jekyllrb.com/docs/home/ (Jekyll)
   [4]: http://mustache.github.io/ (Mustache)
   [5]: http://www.json.org/
   [6]: http://apievangelist.com/2012/08/02/the-apis-that-i-depend-on-for-my-business/ (I depend on multiple APIs)
   [7]: https://scraperwiki.com/
   [8]: http://www.jsoneditoronline.org/ (JSON Editor Online)
   [9]: http://kinlane.github.io/talks/
   [10]: http://imakewebthings.com/deck.js/ (deck.js)
   [11]: http://lab.hakim.se/reveal-js/ (reveal.js)
   [12]: http://github.com (Github)
   [13]: http://pages.github.com/
   [14]: http://aws.amazon.com/s3/
   [15]: https://www.dropbox.com/

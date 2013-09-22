---
layout: post
title: "Why Don't I Have Easy Access to all My Online Personal Data"
url: 'http://kinlane.com/2012/09/01/why-dont-i-have-easy-access-to-all-my-online-personal-data/'
image: ''
---

<img src="https://s3.amazonaws.com/kinlane-productions/facebook/Facebook+Download+Your+Archive.png" alt="" width="300" align="right" />

I was just downloading all of my Facebook data. You can [go under your account settings and there is a little link][1] that lets you download everything.  It takes some time to generate a full archive, but once my archive is ready, they’ll email me and I can get at my data and see what the download format looks like.

While waiting, I wanted to see what Google had to offer. Google has an amazing [acount management dashboard][2] which provides you access to your settings, some of the data, but Google is also working on their [takeout service][3] which gives you downloads for individual services and across multiple services.

That is a pretty good start. Two of my biggest networks allow me to download data. I wasn't so lucky with the next four:

  * Twitter - No
  * Instagram - No
  * Foursquare - No
  * LinkedIn - Some (just your connections)

I use all six of these services daily. It bums me out that I can’t get out my own data. Of course all of these services have an API, which allows developers to get at my data, but even [Twitter’s API doesn’t give me full access to all my accounts data][4].

<img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/ifthisthenthat/IFTTT-My-Recipes.png" alt="" width="300" align="right" />

I want access to a data store of all my [Facebook][5], [Google][6], [Twitter][7], [Instagram][8], [Foursquare][9] and [LinkedIn][10] data in a single location. There are software available trying to solve this problem such as [ThinkUp][11] or [The Locker Project][12]. As with APIs, these solutions require you to be a developer. (I see ThinkUp has a cloud solution now)

At this point I’m thinking about how to build an application using [Singly][13], one that allows me to pull posts, tweets, photos, friends and other vital personal data into a single store.  I need to think it through.

Then I really start questioning the storage of all of my social data. Do I really even want it all in one location? Do I just want it in another location, a sort of plan B. It really depends on the data. I guess I have to think about each service and how I want the data replicated, moved, syndicated or otherwise. This is beginning to sound a lot like [API automation][14] to me and not just data liberation.

I hate ending a post, without wrapping up an idea properly.  I'll just have to work out in another post, but then again that is why this is on my personal blog and not API Evangelist or API Voice.

   [1]: https://www.facebook.com/download
   [2]: https://www.google.com/dashboard
   [3]: https://www.google.com/takeout/ (takeout service)
   [4]: http://apivoice.com/2012/06/29/twitter-continues-to-restrict-access-to-our-tweets/ (Twitter’s API doesn’t give me full access to all my accounts data)
   [5]: https://www.singly.com/docs/facebook (Facebook)
   [6]: https://www.singly.com/docs/gcontacts (Google)
   [7]: https://www.singly.com/docs/twitter (Twitter)
   [8]: https://www.singly.com/docs/instagram (Instagram)
   [9]: https://www.singly.com/docs/foursquare (Foursquare)
   [10]: https://www.singly.com/docs/linkedin (LinkedIn)
   [11]: http://thinkupapp.com/ (ThinkUp)
   [12]: http://lockerproject.org/ (The Locker Project)
   [13]: https://singly.com (Singly)
   [14]: http://apievangelist.com/2012/08/21/api-automation-platforms/ (API Automation)

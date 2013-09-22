---
layout: post
title: "Instagram Photo Book [Idea]"
url: 'http://kinlane.com/2011/01/19/instagram-photo-book-idea/'
image: 'http://kinlane-productions.s3.amazonaws.com/instagram.PNG'
---

_This is another post in my [API][1] Ideas series, I'm posting all my ideas for applications that could be built using the [Mimeo][2] Connect [Cloud Print][3] API._

Instagr.am a popular [Photo][4] sharing [IPhone][5] applications has become popular among the highly influential IPhone user base.

Instagram allows you to take photos on your IPhone apply unique filters to them which change color, brightness, borders and create an entirely new version of your photo. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/instagram.PNG" alt="" width="250" align="right" /> The mobile app allows you to enhance the average photos taken with your IPhone and quickly share to [Twitter][6], [Facebook][7], Flickr or Tumblr.

These photos can be very unique, breathing new life into your digital photo taking.

The quality of the photos and passion of the user base calls for creation of an Instagram Photo Book tool, allowing users to build photo books online and have them delivered to their homes.

A [Rogue Instagram API][8] was exposed using the same mechanims the IPhone app uses, but was [quickly shut down by the company][9]. Without an Instagram API, it makes building a photo book difficult, but not impossible.

I was able to pull my photos via my Flickr account. Using the [Flickr API][10] I was able to pull all instagr.am photos using the tag _instagram app_.

Then I was able to assemble the photos onto an HTML page with desired formatting, once formatted I render the HTML to a PDF and send to the Mimeo Connect Cloud Print API Proofing Service.

After proofing I'm able to preview my Instagram Photo Book and send to the Mimeo Connect Cloud Print API Order Service and actually order my physical Instagram Photo Book and have it delivered.

There is definitely a huge opportunity for some entrepreneur out there to build a Instagram Photo Book Web Application.

   [1]: http://www.apievangelist.com/
   [2]: http://www.mimeo.com
   [3]: http://www.kinlane.com/category/cloud-computing/cloud-print/
   [4]: http://www.kinlane.com/category/publishing/
   [5]: http://www.kinlane.com/category/mobile/iphone/
   [6]: http://www.kinlane.com/category/twitter/
   [7]: http://www.kinlane.com/category/facebook/
   [8]: http://www.kinlane.com/2010/12/instagram-launches-api/
   [9]: http://blog.programmableweb.com/2011/01/12/instagram-shuts-down-third-party-developers-plans-official-api/
   [10]: http://www.apievangelist.com/api-detail.php?API_ID=116

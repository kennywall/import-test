---
layout: post
title: Instagram Photo Book [Idea]
url: http://apievangelist.com/2011/01/19/instagram-photo-book-idea/
source: http://apievangelist.com/2011/01/19/instagram-photo-book-idea/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/instagram.PNG
---
{% include JB/setup %}This is another post in my API Ideas series, I'm posting all my ideas for applications that could be built using the Mimeo Connect Cloud Print API.
Instagr.am a popular Photo sharing IPhone applications has become popular among the highly influential IPhone user base.
Instagram allows you to take photos on your IPhone apply unique filters to them which change color, brightness, borders and create an entirely new version of your photo.

The mobile app allows you to enhance the average photos taken with your IPhone and quickly share to Twitter, Facebook, Flickr or Tumblr.
These photos can be very unique, breathing new life into your digital photo taking.
The quality of the photos and passion of the user base calls for creation of an Instagram Photo Book tool, allowing users to build photo books online and have them delivered to their homes.
A Rogue Instagram API was exposed using the same mechanims the IPhone app uses, but was quickly shut down by the company.  Without an Instagram API, it makes building a photo book difficult, but not impossible.
I was able to pull my photos via my Flickr account.  Using the Flickr API I was able to pull all instagr.am photos using the tag instagram app.
Then I was able to assemble the photos onto an HTML page with desired formatting, once formatted I render the HTML to a PDF and send to the Mimeo Connect Cloud Print API Proofing Service.
After proofing I'm able to preview my Instagram Photo Book and send to the Mimeo Connect Cloud Print API Order Service and actually order my physical Instagram Photo Book and have it delivered.
There is definitely a huge opportunity for some entrepreneur out there to build a Instagram Photo Book Web Application.
---
layout: post
title: "Read It Later Binder with Instapaper and Mimeo Connect"
url: 'http://kinlane.com/2011/06/02/read-it-later-binder-with-instaper-and-mimeo-connect/'
image: 'http://kinlane-productions.s3.amazonaws.com/instapaper.png'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/instapaper.png" alt="" width="125" align="right" />I do a lot of reading on topics ranging from APIs to Printing. I read articles, white-papers and other news from a wide variety of sources on my desktop, laptop, tablet and my mobile phone.

When I come across longer articles I tend to save them for reading later, using a tool called [Instapaper][1].

With a single click, Instapaper allows me to save an article from any web page, and read it later. I can do this from any of my computers, tables or IPhone. Then when ready I can go to my Instapaper account, in my browser or using my IPhone or IPad application and read the post in its entirety.

This type of read it later format has replaced my Sunday Paper. I tend to sit down on Saturday and Sunday mornings and read the longer pieces I didn't have time for during my busy week.

This type of reading material is well suited for my IPad, but this isn't always the perfect tool for other readers. Some people would prefer having in a printed format to take wherever they go, and be completely offline.

Last week I came up with the idea for a [Friday read it later binder with Instapaper][2]. This week I made that idea a reality. I put together a prototype of what this could look like using three separate APIs:

  * **[Instapaper API][3]** \- I pull all my unread bookmarks from Instapaper using their API. Instapaper requires you have a full account for this functionality, but it costs $12 / year. Definitely worth it.
  * **[PDF Crowd API][4]** \- Once I have all the latest bookmarked articles, papers, etc from Instapaper I use PDF Crowd to create a PDF from them.
  * **[Mimeo Connect Cloud Print API][5]** \- Using Mimeo Connect I take the PDF I've created, pass the URL to the REST API along with the document ID for the type of binder or binding I want. I pass the API my shipping addres, get the shipping options returned, and place order for my binder.
<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/mimeo_connect_logo.jpg" alt="" width="175" align="right" />Using Instapapers powerful suite of bookmarking tools and three separate APIs I can produce a binder or booklet of articles, white-papers and other news from the week for easy reading over the weekend.

If I get this in by Thursday night I can have the printed copy on my desk Friday before I leave for the weekend. In the northeast same day shipping is even possible.

You can download the [PHP code for this prototype at Github][6], and build your own read it later application using Mimeo Connect.

 

######  Related articles

  * [Instapaper Full API with XAuth - PHP Class][7] (kinlane.com)
  * [Read It Later Binder Using Instapaper][8] (kinlane.com)
  * [Instapaper Mobile App and API Strategy][9] (apievangelist.com)

   [1]: http://www.instapaper.com (Instpaper)
   [2]: ../../projects/idea_detail.php?ID=13 (Friday Read it Later Binder with Instapaper)
   [3]: http://www.instapaper.com/api/full (Instapaper API)
   [4]: https://pdfcrowd.com/html-to-pdf-api/ (PDF Crowd API)
   [5]: ../../ (Mimeo Connect Cloud Print API)
   [6]: https://github.com/mimeoconnect/InstapaperBinder (PHP Code for this at Github)
   [7]: http://www.kinlane.com/2011/06/instapaper-full-api-with-xauth-php-class/
   [8]: http://www.kinlane.com/2011/05/read-it-later-binder-using-instapaper/
   [9]: http://blog.apievangelist.com/2011/04/28/instapaper-mobile-app-and-api-strategy/

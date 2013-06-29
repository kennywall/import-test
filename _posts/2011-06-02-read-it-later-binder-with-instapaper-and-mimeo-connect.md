---
layout: post
title: Read It Later Binder with Instapaper and Mimeo Connect
url: http://kinlane.com/2011/06/02/read-it-later-binder-with-instaper-and-mimeo-connect/
image: http://kinlane-productions.s3.amazonaws.com/instapaper.png
---
{% include JB/setup %}

When I come across longer articles I tend to save them for reading later, using a tool called Instapaper.

With a single click, Instapaper allows me to save an article from any web page, and read it later. I can do this from any of my computers, tables or IPhone. Then when ready I can go to my Instapaper account, in my browser or using my IPhone or IPad application and read the post in its entirety.
This type of read it later format has replaced my Sunday Paper. I tend to sit down on Saturday and Sunday mornings and read the longer pieces I didn't have time for during my busy week.
This type of reading material is well suited for my IPad, but this isn't always the perfect tool for other readers. Some people would prefer having in a printed format to take wherever they go, and be completely offline. 
Last week I came up with the idea for a Friday read it later binder with Instapaper. This week I made that idea a reality. I put together a prototype of what this could look like using three separate APIs:

	Instapaper API - I pull all my unread bookmarks from Instapaper using their API. Instapaper requires you have a full account for this functionality, but it costs $12 / year. Definitely worth it.
	PDF Crowd API - Once I have all the latest bookmarked articles, papers, etc from Instapaper I use PDF Crowd to create a PDF from them.
	Mimeo Connect Cloud Print API - Using Mimeo Connect I take the PDF I've created, pass the URL to the REST API along with the document ID for the type of binder or binding I want. I pass the API my shipping addres, get the shipping options returned, and place order for my binder.

Using Instapapers powerful suite of bookmarking tools and three separate APIs I can produce a binder or booklet of articles, white-papers and other news from the week for easy reading over the weekend.
If I get this in by Thursday night I can have the printed copy on my desk Friday before I leave for the weekend. In the northeast same day shipping is even possible.
You can download the PHP code for this prototype at Github, and build your own read it later application using Mimeo Connect.

&nbsp;
Related articles

	Instapaper Full API with XAuth - PHP Class (kinlane.com)
	Read It Later Binder Using Instapaper (kinlane.com)
	Instapaper Mobile App and API Strategy (apievangelist.com)

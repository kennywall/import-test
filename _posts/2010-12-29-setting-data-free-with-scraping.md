---
layout: post
title: "Setting Data Free with Scraping"
url: 'http://kinlane.com/2010/12/29/setting-data-free-with-scraping/'
image: 'http://kinlane-productions.s3.amazonaws.com/ScraperWiki-Logo.jpg'
---

<img src="http://kinlane-productions.s3.amazonaws.com/ScraperWiki-Logo.jpg" alt="" align="right" />I was just reading [Setting Government Data Free with ScraperWiki][1] from [ProgrammableWeb][2]. It led me to start playing with [ScraperWiki][3]:

  * [Scraper][4]: a computer program that copies structured information from webpages into a database
  * [ScraperWiki][5]: a website where people can write and repair public web scrapers and invent uses for the data
With 20 years of experience with databases, I have love of data and tools that make data more accessible. Scraping is an important tool in the liberation of data from web-based sources.

The data often is restricted by a lack of skills or resources by the owning party. They just don't have time or the understanding on how to publish the data so it is easily accessed and consumed. Other times they may purposely make it difficult to access.

I have a pretty mature set of scraping scripts that allow me to pull web pages, consume, iterate and parse the content. I then store as XML files on [Amazon S3][6], relational tables in [Amazon RDS][7] or key-value pairs in [Amazon SimpleDB][8].

I like what [ScraperWiki][3] is doing with not only democratizing data, but democratizing the tools and places to store the data. There is a lot of work to be done in liberating data for government, corporate and non-profit groups. We need all the people, tools, and standard processes we can get.

   [1]: http://blog.programmableweb.com/2010/12/29/setting-government-data-free-with-scraperwiki/
   [2]: http://www.programmableweb.com
   [3]: http://scraperwiki.com/
   [4]: http://en.wikipedia.org/wiki/Web_scraping
   [5]: http://scraperwiki.com/about/
   [6]: http://www.kinlane.com/category/amazon/amazon-s3/
   [7]: http://www.kinlane.com/category/amazon/amazon-relational-database/
   [8]: http://www.kinlane.com/category/amazon/amazon-simple-database/

---
layout: post
title: Business Directory for your Local Wordpress Blog or Site
url: http://apievangelist.com/2012/02/28/business-directory-for-your-local-wordpress-blog-or-site/
source: http://apievangelist.com/2012/02/28/business-directory-for-your-local-wordpress-blog-or-site/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/wordpress-logo.jpg
---
{% include JB/setup %}
I finished the first version of a business directory WordPress plugin that you can use to deploy a local directory for your Wordpress site or blog.  I wanted to make an easy way for non-developers, to launch a local directory for one or multiple business categories.
The Hyp3rL0cal Wordpress Plugin uses two APIs:

CityGrid Places API
CityGrid Advertising API

To install the CityGrid Hyp3rL0cal Wordpress Plugin you have two options:

Search for it and install using the Plugin Search in your Wordpress site (this is the easiest).
Download it from the Wordpress plugin directory or via Github, and upload using the "plugin upload" in your Wordpress site.

Once installed you should see a new menu in your Wordpress admin menu, called CityGrid.  It contains an overview of the plugin and a setting page for configuring your Wordpress directory.

Using the settings page you can configure five elements of your local business directory:

CityGrid Publisher Code - The API key that gives you access to CityGrid business data.
Directory Label - What your directory will be called on your sites menu.
Where - A location of "where" you want to provide a search for, this can include: Cities, Neighborhoods, Zip Codes, Metro Areas, Addresses and Intersections.
What - Keywords separated by commas (pizza, pubs, hair salon, auto parts). Each keyword or phrase will create new page and directory.
Ads - Whether or not you want to show ads on your site.

I tried to find strike a balance between simplicity, while also giving site owners a very robust local directory for their site.  My goal is to empower non-developers with the ability to launch local business directories for any topic or geographic location at a city level.
This is just version 1.0 of the CityGrid Hyp3rL0cal Wordpress Plugin, so if you find problems, or there are things you would like to see in future versions, please tweet your feedback @citygridapiteam or leave comments on the CityGrid Dev Talk Forum.
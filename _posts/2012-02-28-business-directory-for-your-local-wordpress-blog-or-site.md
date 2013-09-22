---
layout: post
title: "Business Directory for your Local Wordpress Blog or Site"
url: 'http://kinlane.com/2012/02/28/business-directory-for-your-local-wordpress-blog-or-site/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/wordpress-logo.jpg'
---

<img class="c1" src="https://s3.amazonaws.com/kinlane-productions/wordpress.jpg" alt="" width="200" align="right" />

I finished the first version of a [business directory WordPress plugin][1] that you can use to deploy a local directory for your Wordpress site or blog. I wanted to make an easy way for non-developers, to launch a local directory for one or multiple business categories.

The Hyp3rL0cal Wordpress Plugin uses two APIs:

  * [CityGrid Places API][2]
  * [CityGrid Advertising API][3]

To install the CityGrid Hyp3rL0cal Wordpress Plugin you have two options:

  * Search for it and install using the Plugin Search in your Wordpress site (this is the easiest).
  * Download it from the [Wordpress plugin directory][4] or via [Github][5], and upload using the "plugin upload" in your Wordpress site.

Once installed you should see a new menu in your Wordpress admin menu, called CityGrid. It contains an overview of the plugin and a setting page for configuring your Wordpress directory.

<img class="c1" src="https://s3.amazonaws.com/kinlane-productions/citygrid/citygrid_logo.jpg" alt="" width="250" align="right" />

Using the settings page you can configure five elements of your local business directory:

  * **CityGrid Publisher Code** \- The API key that gives you access to CityGrid business data.
  * **Directory Label** \- What your directory will be called on your sites menu.
  * **Where** \- A location of "where" you want to provide a search for, this can include: Cities, Neighborhoods, Zip Codes, Metro Areas, Addresses and Intersections.
  * **What** \- Keywords separated by commas (pizza, pubs, hair salon, auto parts). Each keyword or phrase will create new page and directory.
  * **Ads** \- Whether or not you want to show ads on your site.

I tried to find strike a balance between simplicity, while also giving site owners a very robust local directory for their site. My goal is to empower non-developers with the ability to launch local business directories for any topic or geographic location at a city level.

This is just version 1.0 of the [CityGrid Hyp3rL0cal Wordpress Plugin][6], so if you find problems, or there are things you would like to see in future versions, please tweet your feedback [@citygridapiteam][7] or leave comments on the [CityGrid Dev Talk Forum][8].

   [1]: http://wordpress-local-directory.hyp3rl0cal.com/ (business directory wordpress plugin)
   [2]: http://docs.citygridmedia.com/display/citygridv2/Places%20API (Places API)
   [3]: http://docs.citygridmedia.com/display/citygridv2/Ads%20by%20CityGrid (CityGrid Advertising API)
   [4]: http://wordpress.org/extend/plugins/hyp3rl0cal-wordpress-plugin/ (CityGrid Hyp3rL0cal Wordpress Plugin)
   [5]: https://github.com/kinlane/Hyp3rL0cal-Wordpress-Plugin (CityGrid hyp3rl0cal Wordpress Plugin on Github)
   [6]: http://wordpress-local-directory.hyp3rl0cal.com/ (CityGrid Hyp3rL0cal Wordpress Plugin)
   [7]: https://twitter.com/#!/CityGridAPITeam (@citygridapiteam)
   [8]: https://groups.google.com/forum/?hl=en#!forum/citygrid-dev-talk (CityGrid Dev Talk Forum)

---
layout: post
title: Service Offered by Local Social Mobile API Providers
url: http://kinlane.com/2012/01/03/service-offered-by-local-social-mobile-api-providers/
image: http://kinlane-productions.s3.amazonaws.com/hyp3rl0cal/local-search-map-pin.png
---
{% include JB/setup %}
To kick-off my role as API Evangelist at CityGrid, I took a quick walk through the world of location and places API.
The CityGrid API centers around places API which provides rich local business data via a RESTful API. So getting familiar with other location and places API is critical to my role.
While going through each of these APIs in the space I flushed out what I'd consider the high levels areas that these APIs offer. This list is a work in progress, with a goal in helping see the industry, and potentially identify where players are leading the industry, and where there are gaps.
Of course it all starts with places information. Rich content about businesses and other geographic points of interest. CityGrid, Google, Yahoo, Bing and other players like Foursquare, SimpleGeo, InfoChimps and Factual all bring places data to the table.
CityGrid and Foursquare also bring merchant APIs to the game, allowing businesses to manage their profile data as well as how it gets syndicated across many networks.
Along with places data there are various geo related services that are offered across these APIs:


	GeoCoding
	Directions
	Distance
	Elevation
	Geofencing

The next area I'm grouping location services under would be other content directly related to specific places, pulled through APIs:

	Reviews
	Offers
	Images
	Videos
	Menus
	Editorials

After location and business related content I'd say there is a growing pool of related content that may not be directly associated with a business or location, but provide context, and augment places data making it more meaningful to users:


	Weather
	Demographics
	Wikipedia
	Neighborhood
	Tagging

That isn't a complete list of contextual places content, but a couple of quick ones I found. I will explore this area more later.
After content I'm seeing very distinct actions that users can take around location and places data. Again, I'm sure there are more of these, but here is a short list of location actions:

	Check-In
	Push Notifications
	Recommendations

You can't talk about location data without bringing in mapping. Google Maps is the most well known mapping API, but there are several providers that have JavaScript and Image based location mapping that developers can use in their web and mobile applications.
Next I broke out a group of location specific services, that provide location tools for developers that provide current location of users as well as tools for recording the history of users. There are also robust tools for doing look-ups of location based upon IP address, longitude and latitude and physical address.
While doing the review of location and places APIs I also notice mobile specific tools offered by a few of the provider like mobile network probe for identifying network quality, and mobile specific SDKs, making sure mobile developers can take maximize their usage of services.
Last but not least are a handful of social tools that bring the social to local, mobile, social. Mostly these are hooks into Twitter and Facebook friend networks, but some bring their own social networks to the table, such as Foursquare.
This is just my first draft of the different areas of APIs, tools and services provide by location and places API providers. Its by no means a complete listing, and is meant to give me a start in understanding and organizing the local, mobile, social API space.
If you know of any areas I'm missing and should be considering, please let me know.
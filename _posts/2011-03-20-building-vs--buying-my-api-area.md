---
layout: post
title: Building vs  Buying My API Area
url: http://kinlane.com/2011/03/20/building-vs-buying-my-api-area/
image: http://kinlane-productions.s3.amazonaws.com/api-service-providers/mashery-logo.png
---
{% include JB/setup %}
For the last four months I've been on a pretty wild ride trying to find a solution to delivering the Mimeo Connect Print API and its community.
I looked at the three major API service providers, Mashery, Apigee, and 3Scale.  I also took a look at a new player, Mashape.
After four months, whats the plan? I'm going to build my own API area.
Keep in mind, I already have a REST API with everything I need.  I just don't have any supporting area, metrics, or security tools.
I really like what the API service providers offer.

	Mashery, provides a powerful set of API management tools, resource and an extremely knowledgable team.   They also offer a lot of exposure for your API.
	Apigee, provides a comparable set of tools to Mashery, with a more polished, "enterprisey" feel to it.  They don't seem to have the same public presence Mashery has, but are quickly catching up.

Both Mashery and Apigee proxies your API and acts as middleman between your data or functionality and the world.

	3Scale provides similar tools and services as Mashery and Apigee, but does this using a plugin you install on your server.  Then you use the 3Scale platform to meter calls and manage your community.
	Mashape provides a pluging for deploying a RESTful API, but lacks some of the robust community tools offered by other providers. Although, Mashape does provide a marketplaceenvironmentfor APIs to get exposure.

All four API service providers offer some powerful tools for delivering our APIs.

Really it came down to cost.

	Cost of hourly development for custom API work.
	Cost of per transactions on REST API.

I already have an API.  I just needs some metrics and an API area around it. Then I'd be open for business. So I'm a little ahead than other API operators.
Next I have a lot of learning to do around our API.  Yes, any API owner does.  I have some other considerations when it comes to document building, printing and delivery costs that make my learning potentially very expensive. API to manufacturing isn't quite a proven area.
This makes every hour spent and every API call made during research and development potentially costly.

I just couldn't sell the cost / value proposition to my executive team and justify the money I'd be spending with these API service provider.
So I am:

	Using my existing REST API
	Pulling together my own API area from various third party tools and some custom coding.

Then I am going to spend the next six months learning, understanding whats possible, playing with different prototypes and getting to know my developer community.
Then we'll re-evaluate and see if an API service provider is right for me.
&nbsp;

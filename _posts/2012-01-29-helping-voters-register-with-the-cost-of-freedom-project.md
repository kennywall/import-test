---
layout: post
title: Helping Voters Register with the Cost of Freedom Project
url: http://kinlane.com/2012/01/29/helping-voters-register-with-the-cost-of-freedom-project/
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/Cost-Of-Freedom-Map.png
---
{% include JB/setup %}

Last week during the&nbsp;Hackathon for Social Good in New York City, I was fortunate enough to be connected with Faye Anderson (@andersonatlarge) of the&nbsp;Cost of Freedom Project. &nbsp;The Hackathon for Social Good was put on my&nbsp;WebVisions, using the hackathon model to further projects that are making a social impact in our lives.
The Cost of Freedom Project is centered around providing the necessary information and resources needed by U.S citizens to be able to vote in the 2012 elections, primarily targeted the 5 states that have strict laws requiring voters to show a government issued photo ID in order to vote.
When it comes to making a social impact, Faye&rsquo;s project is a shining example, and I couldn&rsquo;t ignore her need for a hacker to move her project forward. &nbsp;After hearing her pitch, I joined her project team which included Lori Widelitz-Cavallucci (@lwcavallucci) a UX Designer, and Jack Aboutboul (@jackfoundation), Developer Evangelist from Twilio.
As Lori and Faye got to work on the site layout and user experience I started setting up the back-end that would be necessary to run the app:

Amazon EC2 Instance Running Fedora Linux and Apache Web Server &nbsp;PHP 5.3
Twitter Bootstrap
DNS for Domain Setup

By the end of the Hackathon we had a site layout, with all pages setup with initial content. &nbsp;All the site content is editable from a Google spreadsheet allowing Faye to maintain control over her content and crowsdsource the management of content using the spreadsheet interface.
The site uses CityGrid to pull vital record offices by state, county voter registration and local DMV offices when a user enters their city and zip code.
The Cost of Freedom Project is a great example of what you can pull together at a hackathon, but also the wide range of apps you can build using CityGrid data. &nbsp;Sites do not have to be local directories,&nbsp;CityGrid places data&nbsp;can be used to build informational sites that add value to almost any process.

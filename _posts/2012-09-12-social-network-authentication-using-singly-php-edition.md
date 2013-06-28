---
layout: post
title: Social Network Authentication Using Singly (PHP Edition)
url: http://apievangelist.com/2012/09/12/social-network-authentication-using-singly-php-edition/
source: http://apievangelist.com/2012/09/12/social-network-authentication-using-singly-php-edition/
domain: apievangelist.com
image: 
---
{% include JB/setup %}
As an active user of a variety of cloud services I&rsquo;ve become very accustom to authenticating using my social networks, such as Facebook, Twitter, LInkedin or Github,  rather than creating yet another new account.
If I want access to an online service, and it allows me to authenticate using my social networks, I make a quick assumption on which one is best to use, click on link, give the application appropriate oAuth approval, and begin using the service. I can revoke their access at any time when I manage my oAuth permissions in the social network.
I want to make this default for users of my websites, apps and APIs--allowing them authenticate using six social networks:




Facebook

Foursquare

Github



Instagram

LinkedIn

Twitter



Singly has made this nice and easy!




Step 1 - Sign up for Singly



Step 2 - Create New Singly App





Step 3 - Create Social Network Apps.  This part seems like it is a lot of work, but once done...it is sweet.  You need to create an app for each one of the six social networks you will be allowing authentication:




















Singly has great instructions to walk you through this process.  It will only take you about 5-10 minutes.  And once you are done, you will have one API key to access all six of these APIs.
I built a prototype PHP application that demonstrates this process, you can download on Github.  Once downloaded, all you need to do is add your Singly app keys, and Site URL into the config file.
I provide six links with icons triggering the social network authentication via Singly:

Then I provide six separate authentication callback handlers.  I keep them separate, because I intend to do separate handling for each social network within these callbacks in the near future.
All six callback handlers just set a session with your authentication information and redirect you back to home page for display.  What&rsquo;s next is up to you.
I will be adding more to this social network authentication prototype in the near future.  A couple of things I would like to do is have a display profile widget and some sort of ranking of users by social network.
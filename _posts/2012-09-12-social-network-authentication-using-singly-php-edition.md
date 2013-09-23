---
layout: post
title: "Social Network Authentication Using Singly (PHP Edition)"
url: 'http://kinlane.com/2012/09/12/social-network-authentication-using-singly-php-edition/'
image: ''
---

[<img class="c1" src="https://s3.amazonaws.com/kinlane-productions/singly/singly-twitter-linkedin-github-facebook-authentication.png" alt="" width="175" align="right" />][1]

As an active user of a variety of cloud services I’ve become very accustom to authenticating using my social networks, such as Facebook, Twitter, LInkedin or Github, rather than creating yet another new account.

If I want access to an online service, and it allows me to authenticate using my social networks, I make a quick assumption on which one is best to use, click on link, give the application appropriate oAuth approval, and begin using the service. I can revoke their access at any time when I manage my oAuth permissions in the social network.

I want to make this default for users of my websites, apps and APIs--allowing them authenticate using six social networks:

[<img src="https://s3.amazonaws.com/kinlane-productions/icons/facebook.png" alt="" width="25" />][2]

**[Facebook**][2]

[<img src="https://s3.amazonaws.com/kinlane-productions/icons/foursquare.png" alt="" width="25" />][3]

**[Foursquare][3]**

[<img src="https://s3.amazonaws.com/kinlane-productions/icons/github.png" alt="" width="25" />][4]

**[Github][4]**

[<img src="https://s3.amazonaws.com/kinlane-productions/icons/instagram.png" alt="" width="25" />][5]

**[Instagram][5]**

[<img src="https://s3.amazonaws.com/kinlane-productions/icons/linkedin.png" alt="" width="25" />][6]

**[LinkedIn][7]**

[<img src="https://s3.amazonaws.com/kinlane-productions/icons/twitter-2.png" alt="" width="25" />][8]

**[Twitter][8]**

**Singly has made this nice and easy!**

**Step 1 - [Sign up for Singly][9]**

[<img class="c4" src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Sign-Up.png" alt="" width="250" />][9]

**Step 2 - [Create New Singly App][10]**

[<img class="c4" src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Create-New-App.png" alt="" width="250" />][10]

**Step 3 - Create Social Network Apps.** This part seems like it is a lot of work, but once done...it is sweet. You need to create an app for each one of the six social networks you will be allowing authentication:

<img src="https://s3.amazonaws.com/kinlane-productions/icons/facebook.png" alt="" width="25" />

<img src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Facebook-New-App.png" alt="" width="150" />

<img src="https://s3.amazonaws.com/kinlane-productions/icons/foursquare.png" alt="" width="25" />

<img src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Foursquare-New-App.png" alt="" width="150" />

<img src="https://s3.amazonaws.com/kinlane-productions/icons/github.png" alt="" width="25" />

<img src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Github-New-App.png" alt="" width="150" />

<img src="https://s3.amazonaws.com/kinlane-productions/icons/instagram.png" alt="" width="25" />

<img src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Instagram-New-App.png" alt="" width="150" />

<img src="https://s3.amazonaws.com/kinlane-productions/icons/linkedin.png" alt="" width="25" />

<img src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-LinkedIn-New-App.png" alt="" width="150" />

<img src="https://s3.amazonaws.com/kinlane-productions/icons/twitter-2.png" alt="" width="25" />

<img src="https://s3.amazonaws.com/kinlane-productions/singly/Singly-Twitter-New-App.png" alt="" width="150" />

Singly has great instructions to walk you through this process. It will only take you about 5-10 minutes. And once you are done, you will have one API key to access all six of these APIs.

I built a [prototype PHP application][11] that demonstrates this process, you can [download on Github][12]. Once downloaded, all you need to do is add your Singly app keys, and Site URL into the config file.

I provide six links with icons triggering the social network authentication via Singly:

Then I provide [six separate authentication callback handlers][13]. I keep them separate, because I intend to do separate handling for each social network within these callbacks in the near future.

All six callback handlers just set a session with your authentication information and redirect you back to home page for display. What’s next is up to you.

I will be adding more to this social network authentication prototype in the near future. A couple of things I would like to do is have a display profile widget and some sort of ranking of users by social network.

   [1]: http://www.singly.com/
   [2]: https://singly.com/docs/facebook (Facebook)
   [3]: https://singly.com/docs/foursquare (Foursquare)
   [4]: https://singly.com/docs/github (Github)
   [5]: https://singly.com/docs/instagram (Instagram)
   [6]: https://singly.com/docs/linkedin (LinkedIn)
   [7]: https://singly.com/docs/linkedin
   [8]: https://singly.com/docs/twitter (Twitter)
   [9]: https://singly.com/signup?section=header
   [10]: https://singly.com/apps/new
   [11]: http://singly-authentication.laneworks.net/
   [12]: https://github.com/kinlane/singly-social-authentication-php
   [13]: https://github.com/kinlane/singly-social-authentication-php/tree/master/auth

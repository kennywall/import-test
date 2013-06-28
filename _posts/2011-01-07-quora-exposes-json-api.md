---
layout: post
title: Quora Exposes JSON API
url: http://apievangelist.com/2011/01/07/2497/
source: http://apievangelist.com/2011/01/07/2497/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/quora-logo.jpg
---
{% include JB/setup %}<p>Quora has exposed a JSON-based data API that allows users to access data about a currently logged-in user.
To  request particular fields about the currently logged-in user, you can  add fields to a query string and append to  http://api.quora.com/api/logged_in_user.
Currently supported fields include:


	Inbox
	Followers
	Following
	Notifs

Here is an example call:  http://api.quora.com/api/logged_in_user?fields=inbox,notifs
This will return Inbox and Notification related information for the authenticated user.
This  is not a full-blown API release by Quora.  Quora engineer Edmond Lau  posted information on Quora about the API, stating that it is in its  alpha stage and is only meant to support existing Quora Chrome and  Quora Firefox extensions.
Even  though it doesn't have all the supporting elements of an official API  release, the fact that the Q&amp;A startup has established api.quora.com for its use, indicates that it plans to invest more energy around an official Quora API.</p>
<center><p><a href="http://apievangelist.com/2011/01/07/2497/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

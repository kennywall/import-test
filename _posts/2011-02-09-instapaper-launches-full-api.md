---
layout: post
title: Instapaper Launches Full API
url: http://kinlane.com/2011/02/09/instapaper-launches-full-api/
source: http://kinlane.com/2011/02/09/instapaper-launches-full-api/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/instapaper.png
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <a href="http://www.instapaper.com/" target="_blank"><img style="padding: 10px;" src="http://kinlane-productions.s3.amazonaws.com/instapaper.png" alt="" width="175" align="right" /></a><a href=
    "http://www.instapaper.com/" target="_blank">Instapaper</a> just launched a <a href="http://www.instapaper.com/api/full" target="_blank">Full API</a> giving developers access to web pages that
    Instagram users have saved to read later. The API provides full Instapaper account access, but can only access web page bookmarks from paid-subscriber accounts. Those who haven't paid the
    $1/month fee for an Instapaper account will still be able to submit to Instapaper using the <a href="http://www.instapaper.com/api/simple" target="_blank">Instapaper Simple API</a>. The API uses
    oAuth 2.0 for authentication and provide a set of helper libraries to get going. Instapaper API services and endpoints are: <strong>Account / Authentication</strong>
    <ul class="mainlist">
      <li>/api/1/oauth/access_token
      </li>
      <li>/api/1/account/verify_credentials
      </li>
    </ul><strong>Web Page Bookmarks</strong>
    <ul class="mainlist">
      <li>/api/1/bookmarks/list
      </li>
      <li>/api/1/bookmarks/update_read_progress
      </li>
      <li>/api/1/bookmarks/add
      </li>
      <li>/api/1/bookmarks/delete
      </li>
      <li>/api/1/bookmarks/star
      </li>
      <li>/api/1/bookmarks/unstar
      </li>
      <li>/api/1/bookmarks/archive
      </li>
      <li>/api/1/bookmarks/unarchive
      </li>
      <li>/api/1/bookmarks/move
      </li>
      <li>/api/1/bookmarks/get_text
      </li>
    </ul><strong>Folders</strong>
    <ul class="mainlist">
      <li>/api/1/folders/list
      </li>
      <li>/api/1/folders/add
      </li>
      <li>/api/1/folders/delete
      </li>
      <li>/api/1/folders/set_order
      </li>
    </ul>Instapaper has provided some insight on its blog regarding <a href="http://blog.instapaper.com/post/3208433429" target="_blank">why it chose to provide Full API access to data from paid
    accounts</a>. It's a new and interesting perspective to the classic arguement of freemium versus paid accounts. The first application developed using the Full API is <a href=
    "http://wp7wonders.wordpress.com/stacks-for-instapaper/" target="_blank">Stacks for Instapaper</a>, a Windows Phone 7 client. developed by Matthieu Guyonnet-Duluc. More applications are sure to
    come.
  </body>
</html></p>

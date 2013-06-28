---
layout: post
title: HTML 5 Server-Sent Events
url: http://kinlane.com/2010/07/25/html-5-server-sent-events/
source: http://kinlane.com/2010/07/25/html-5-server-sent-events/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/html5.jpg
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <img class="alignnone" style="padding: 15px;" title="HTML5" src="http://kinlane-productions.s3.amazonaws.com/html5.jpg" alt="" width="200" align="right" />As I continue my deep dive into the
    functional side of HTML5 I am learning about Server-Sent Events. Server-Sent Events enable servers to push data to a web page loaded in the browser. Think of it as reverse AJAX. Using the
    EventSource interface you can register and event listener client side. Then server side you send messages using a text/event-stream MIME type. Seems like a much more efficient way of handle
    server side communications. Changes the way you think UI interactions and where events can be initiated.
  </body>
</html></p>

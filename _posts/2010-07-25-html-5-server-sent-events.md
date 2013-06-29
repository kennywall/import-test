---
layout: post
title: HTML 5 Server Sent Events
url: http://kinlane.com/2010/07/25/html-5-server-sent-events/
image: http://kinlane-productions.s3.amazonaws.com/html5.jpg
---
{% include JB/setup %}

Using the EventSource interface you can register and event listener client side.
Then server side you send messages using a text/event-stream MIME type.
Seems like a much more efficient way of handle server side communications. Changes the way you think UI interactions and where events can be initiated.
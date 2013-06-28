---
layout: post
title: EXT JS and Solid Framework
url: http://kinlane.com/2009/04/12/ext-js-and-solid-framework/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
<p>
     I have blogged about my usage of EXT JS Framework. I am adopting it for usage at my company right now and plotting the next stages in our event management software products. It has taken me some considerable work to learn how EXT JS works and how to adopt it for the best usage throughout our software. Some simple things just become real hard for me to do. However the separation of the presentation layer is awesome. I truly feel like I have things separated now. I have built a whole middle layer using CFC in ColdFusion to return JSON to the EXT JS calls. The CFC in turn use stored procedures to handle all the database queries. Its clean....it works. When I want to add a new way at getting at data....I can usually use the same stored procedure and extend an object to return the data I need....slightly configure the EXT JS element...and done. Its definitely a different way of programming...seems more true to the way I like to program. Now I have to sell it to the rest of our development staff.
</p>
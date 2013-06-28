---
layout: post
title: Card Printing API
url: http://kinlane.com/2011/09/05/card-printing-api/
source: http://kinlane.com/2011/09/05/card-printing-api/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo/card-sample-image.png
---
{% include JB/setup %}<img src="http://kinlane-productions.s3.amazonaws.com/mimeo/card-sample-image.png" alt="" width="200" align="right" />We've added a new<a title="API that provides card printing services for developers" href="http://mimeoconnect.3scale.net/wiki/card-printing-api">API that provides card printing services for developers</a>. It enables you to price and order commercially printed cards in different sizes, paper and coating from within your web and mobile applications.<p></p>
These are the different settings currently available for cards:
<ul class="mainlist">
	<li><strong>size</strong>- 4.25×5.5, 5×7, 5.5×8.5, 6×9</li>
	<li><strong>paper</strong>- White Uncoated 60#, White Uncoated 70#, White Uncoated 70# (100% Recycled), White Glossy 80#, White Glossy 100#</li>
	<li><strong>coating</strong>- None, Glossy Coat (Front Only), Glossy Coat (Front and Back), Protective Coat (Front Only), Protective Coat (Front and Back)</li>
</ul>
The Card Printing API has five methods currently:
<ul class="mainlist">
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#Proof-Post">Proof (POST)</a></li>
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#Proof-GET">Proof (GET)</a></li>
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#Quote-GET">Quote (GET)</a></li>
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#ShippingOptions-GET">Shipping Options (GET)</a></li>
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#OrderQuote-GET">Order Quote (GET)</a></li>
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#PlaceOrder-POST">Place Order (POST)</a></li>
	<li><a href="http://mimeoconnect.3scale.net/wiki/card-printing-api#OrderStatus-GET">Order Status (GET)</a></li>
</ul>
You will also find common error codes, PHP code samples. I will be adding more code samples as they become available.
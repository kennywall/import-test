---
layout: post
title: Card Printing API
url: http://kinlane.com/2011/09/05/card-printing-api/
image: http://kinlane-productions.s3.amazonaws.com/mimeo/card-sample-image.png
---
{% include JB/setup %}

These are the different settings currently available for cards:

	size- 4.25�5.5, 5�7, 5.5�8.5, 6�9
	paper- White Uncoated 60#, White Uncoated 70#, White Uncoated 70# (100% Recycled), White Glossy 80#, White Glossy 100#
	coating- None, Glossy Coat (Front Only), Glossy Coat (Front and Back), Protective Coat (Front Only), Protective Coat (Front and Back)

The Card Printing API has five methods currently:

	Proof (POST)
	Proof (GET)
	Quote (GET)
	Shipping Options (GET)
	Order Quote (GET)
	Place Order (POST)
	Order Status (GET)

You will also find common error codes, PHP code samples. I will be adding more code samples as they become available.
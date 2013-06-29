---
layout: post
title: Internet Explorer 9 HTML 5 Support
url: http://kinlane.com/2010/06/27/internet-explorer-9-html-5-support/
image: http://kinlane-productions.s3.amazonaws.com/InternetExplorer.jpg
---
{% include JB/setup %}
Microsoft recently released some new additions to their Windows Internet Explorer Platform, aka. Internet Explorer 9.
They are working hard to support more of the HTML5 standard.
Features Available (Blue are New Releases)

	 Canvas - In the latest Platform Preview we support all Canvas element APIs and most Canvas 2D Context APIs and attributes.
	&lt;video&gt; - MP4 H.264 playback support, using hardware or software decoding and support for WebM software is not included in this release
	&lt;audio&gt; - MP3 and AAC audio support
	window.msPerformance - This API is being worked in partnership with members of the W3C and is subject to change
	IE9 User Agent String
	getElementsByClassName
	characterSet
	HTML5-conformant whitespace handling
	CSS3

	Media Queries
	Selectors (entire module and ::selection)
	Namespaces (all except attribute selectors)
	Backgrounds &amp; Borders
	Color (rgba(), opacity)
	Values &amp; Units


	Web font formats
	HTML5 Events
	DOM Style
	DOM Core
	DOM Traversal
	DOM Range
	DOM L2 Events (complete)
	DOM L3 Events (complete)
	HTML5 Selection
	XHTML Documents - The XHTML mime-type of application/xhtml+xml is now listed in the Accept header of outgoing requests
	Generic XML Improvements (text/xml and application/xml)
	Generic XML documents render contained SVG and XHTML content
	XSLT via &lt;?xml-stylesheet … ?&gt;
	SVG
	ICC v2 and v4 color profiles are supported on images

Features Partially Implemented  (Blue are New  Releases)

	 Canvas

	globalCompositeOperation - The latest Platform Preview does not include support for the globalCompositeOperation attribute.
	DOM Exceptions - The latest Platform Preview does not include support for Canvas 2D Context DOM Exceptions.
	drawFocusRing() - The latest Platform Preview does not include support for the drawFocusRing() Focus management API.


	CSS3 Fonts - font-size-adjust and advanced font features are not supported
	DataURI - Support in script source

Looks like they are trying to get up to speed with other browsers in the HTML 5 support game. I will take some time to compare against the HTML core specs to see how they are doing overall.
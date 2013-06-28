---
layout: post
title: View a PDF in the Browser using JavaScript
url: http://apievangelist.com/2011/06/16/view-a-pdf-in-the-browser-using-javascript/
source: http://apievangelist.com/2011/06/16/view-a-pdf-in-the-browser-using-javascript/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/PDF_red.jpg
---
{% include JB/setup %}
I was sitting in on a session at the O'Reilly Velocity Conference today, by Chris Blizzard of the Mozilla Foundation.  Chris talked covered a wide range of topics in his 20 minutes, but one project really caught my attention.
It is aPDF Reader in JavaScript. The PDF reader(aka pdf.js), is a technology prototype to explore whether the HTML5 platform is complete enough to faithfully and efficiently render the ISO implementation of the Portable Document Format (PDF).
Viewing PDF in the browser has always been a pain in the ass for developers, and generally a bad experience for the user.  Firefox has been working on this for a while, out in the open on Github, but only recently started talking about publicly.
The project is not complete, they are still working on some features like Type1 fonts, gradients, etc.  Along the way, they have had to add some new interfaces to the HTML5 canvas element, and replicate some difficult features of the PDF spec in JavaScript.
Mozilla's goal is to be using pdf.js to render PDFs "natively", within Firefox, enabling the browser to view a majority of the PDF's found on the web today.  Initially pdf.js will be delivered as a Firefox extension, and eventually baking in, and shipping with Firefox.
Mozilla is open-sourcing pdf.js, and releasing under a very liberal 3-clause BSD license.  You can download and get involved over at Github.
Related articles

	Pdf.js: Rendering PDF with HTML5 and JavaScript (andreasgal.com)
	JavaScript: The Definitive Guide (6e) (i-programmer.info)
	Get Them While They're Hot: Firefox 5 Release Candidates Debut (pcworld.com)


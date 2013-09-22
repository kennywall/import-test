---
layout: post
title: "View a PDF in the Browser using JavaScript"
url: 'http://kinlane.com/2011/06/16/view-a-pdf-in-the-browser-using-javascript/'
image: 'http://kinlane-productions.s3.amazonaws.com/PDF_red.jpg'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/PDF_red.jpg" alt="" width="100" align="right" />

I was sitting in on a session at the [O'Reilly Velocity Conference][1] today, by [Chris Blizzard][2] of the [Mozilla Foundation][3]. Chris talked covered a wide range of topics in his 20 minutes, but one project really caught my attention.

It is a[PDF Reader in JavaScript][4]. The PDF reader(aka pdf.js), is a technology prototype to explore whether the HTML5 platform is complete enough to faithfully and efficiently render the ISO implementation of the Portable Document Format (PDF).

Viewing PDF in the browser has always been a pain in the ass for developers, and generally a bad experience for the user. Firefox has been working on this for a while, out in the open on Github, but only recently started talking about publicly.

The project is not complete, they are still working on some features like Type1 fonts, gradients, etc. Along the way, they have had to add some new interfaces to the HTML5 canvas element, and replicate some difficult features of the [PDF][5] spec in JavaScript.

Mozilla's goal is to be using pdf.js to render PDFs "natively", within Firefox, enabling the browser to [view a majority of the PDF's found on the web today][6]. Initially pdf.js will be delivered as a Firefox extension, and eventually baking in, and shipping with Firefox.

Mozilla is open-sourcing pdf.js, and releasing under a very liberal 3-clause BSD license. You can [download and get involved over at Github][7].

######  Related articles

  * [Pdf.js: Rendering PDF with HTML5 and JavaScript][8] (andreasgal.com)
  * [JavaScript: The Definitive Guide (6e)][9] (i-programmer.info)
  * [Get Them While They're Hot: Firefox 5 Release Candidates Debut][10] (pcworld.com)

   [1]: http://velocityconf.com/velocity2011 (Oreilly Velocity Conference)
   [2]: http://en.wikipedia.org/wiki/Christopher_Blizzard (Chris Blizzard)
   [3]: http://www.mozilla.org/foundation/ (Mozilla Foundation)
   [4]: https://github.com/andreasgal/pdf.js (PDF Reader in javascript)
   [5]: http://www.kinlane.com/category/pdf/ (PDF)
   [6]: http://developer.mimeo.com/index.php (view a majority of the PDF's found on the web today)
   [7]: https://github.com/andreasgal/pdf.js (download and get involved at Github)
   [8]: http://andreasgal.com/2011/06/15/pdf-js/
   [9]: http://www.i-programmer.info/bookreviews/29-javascript/2610-javascript-the-definitive-guide-6e.html
   [10]: http://www.pcworld.com/article/230446/get_them_while_theyre_hot_firefox5_release_candidates_debut.html

---
layout: post
title: "Proofing Print Documents From Box.net"
url: 'http://kinlane.com/2011/02/02/proofing-print-documents-from-box-net/'
image: 'http://kinlane-productions.s3.amazonaws.com/box-net-logo.jpg'
---

I am making my way through each major [cloud storage][1] provider and building demos that pull PDF files from the provider and proofs the file before [printing][2] with [Mimeo][3]. [<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/box-net-logo.jpg" alt="" width="200" align="right" />][4] I have put together a demonstration of how to [pull a PDF file from Box.net and the proof it with Mimeo Connect][5].

You will need:

  * [Box.net Account][4]
  * [Mimeo API Account.][6]
This [Cloud Print][7] demonstration is written in [PHP][8], and uses the [Mimeo Connect Cloud Print API REST Client][9]. [<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />][3] You can download the source code for the Box.netto Mimeo Connect project in the following formats:

  * [git (GitHub Repository) - Box.net to Mimeo Print][10]
  * [svn (Google Code Project - Box.net to Mimeo Print][11]
I will be updating this project when I develop any new code that integrates Box.net and the Mimeo Connect Cloud Print API.

This project currently allows you to pull print files from Box.net and proof them with Mimeo Connect Cloud Print API and preview or view any pages in the PDF as images in Flash or [JQuery Flipbook][12].

   [1]: http://www.kinlane.com/category/cloud-computing/cloud-storage/
   [2]: http://www.kinlane.com/category/publishing/
   [3]: http://www.mimeo.com
   [4]: http://www.box.net
   [5]: http://nimbus2.laneworks.net/functions-pull-pdf-from-box-net-and-prepare-proof.php
   [6]: http://www.mimeo.com/
   [7]: http://www.kinlane.com/category/cloud-computing/cloud-print/
   [8]: http://www.kinlane.com/category/php/
   [9]: https://github.com/mimeoconnect/Mimeo-Connect-Cloud-Print-API---REST-Client
   [10]: https://github.com/mimeoconnect/Mimeo-Box.net
   [11]: https://code.google.com/p/mimeo-box-net/
   [12]: http://www.kinlane.com/2011/01/jquery-powered-flipbook-for-previewing-print-files/

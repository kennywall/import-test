---
layout: post
title: "Proofing Print Documents From Amazon S3"
url: 'http://kinlane.com/2011/01/26/proofing-print-documents-from-amazon-s3/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

I am making my way through each major [cloud storage][1] provider and building demos that pull PDF files from the provider and proofs the file before [printing][2] with [Mimeo][3]. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" /> I have put together a demonstration of how to [pull a PDF file from Amazon S3 and the proof it with Mimeo Connect][4].

You will need:

  * [Amazon Web Services Account][5]
  * [Mimeo API Account.][6]
This [Cloud Print][7] demonstration is written in [PHP][8], and uses the [Mimeo Connect Cloud Print API REST Client][9]. [<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />][3] You can download the source code for the [Amazon S3][10] to Mimeo Connect project in the following formats:

  * [git (GitHub Repository) - Amazon S3 to Mimeo Print][11]
  * [svn (Google Code Project - Amazon S3 to Mimeo Print][12]
I will be updating this project when I develop any new code that integrates Amazon S3 and the Mimeo Connect Cloud Print API.

This project currently allows you to pull print files from Amazon S3 and proof them with Mimeo Connect Cloud Print API and preview or view any pages in the PDF as images in Flash or [JQuery Flipbook][13].

   [1]: http://www.kinlane.com/category/cloud-computing/cloud-storage/
   [2]: http://www.kinlane.com/category/publishing/
   [3]: http://www.mimeo.com
   [4]: http://nimbus2.laneworks.net/functions-pull-pdf-from-amazon-s3-api-and-prepare-proof.php
   [5]: http://aws.amazon.com/
   [6]: http://www.mimeo.com/
   [7]: http://www.kinlane.com/category/cloud-computing/cloud-print/
   [8]: http://www.kinlane.com/category/php/
   [9]: https://github.com/mimeoconnect/Mimeo-Connect-Cloud-Print-API---REST-Client
   [10]: http://www.kinlane.com/category/amazon/amazon-s3/
   [11]: https://github.com/mimeoconnect/mimeo-amazon-s3
   [12]: https://code.google.com/p/amazon-s3-mimeo/
   [13]: http://www.kinlane.com/2011/01/jquery-powered-flipbook-for-previewing-print-files/

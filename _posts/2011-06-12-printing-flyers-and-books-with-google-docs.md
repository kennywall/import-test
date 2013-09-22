---
layout: post
title: "Printing Flyers and Books with Google Docs"
url: 'http://kinlane.com/2011/06/12/printing-brochures-and-books-with-google-docs/'
image: 'http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-2.png'
---

[<img src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-2.png" alt="" width="250" align="right" />][1][Google Apps][2] provides a very powerful document management solution, [Google Docs][3].

With Google Docs you can upload and create many different types of documents. The Google Apps platform also allows users to collaborate, share, translate, download and print documents in Google Apps. This is pretty powerful stuff, when it comes to business publishing and printing.

A couple months ago I built a [prototype of a commercial print application using Google Cloud Print][4]. The platform allows users to sign on and create and / or register cloud printers with Google's Cloud Print (GCP) registry. Google Apps users can then print single sheet, bound document, and binders using Google Cloud Print and Mimeo.com.

I wanted to simplify what I built. So I made some time this last week, to strip out three core pieces of functionality. I wanted to enable developers to do three separate types of simple print integrations:

  * **[Printing Single Sheets][5]** \- Allow printing of brochures, flyers and other single sheet documents to Mimeo.com with GCP.
  * **[Printing Bound Documents][6]** \- Allow printing of books, magazines, newsletters, and other bound documents to Mimeo.com with GCP.
  * **[Print Driver][7]** \- Enable sending print files to Mimeo.com using GCP.
These how-tos are meant to be complete, but simple integration examples with [Google Cloud Print][8].

I want to show users how easily it is to print business documents using Google Cloud Print and your [Mimeo.com][9] account.

These samples are written in PHP, and use the Zen framwork for the Google API integration.

Each how-to, has the samples, and link to the full repositories for download at Github. I'm hoping this help developers get going with self-publishing and print-on-demand using Google Apps, Google Cloud Print and Mimeo.com.

######  Related articles

  * [Mimeo Cloud Printing Building Blocks][10] (kinlane.com)
  * [Mimeo Connect API Ecosystem][11] (kinlane.com)
  * [Mimeo Cloud Print vs. Lulu][12] (kinlane.com)

   [1]: http://developer.mimeo.com/
   [2]: http://www.google.com/apps/intl/en/business/index.html (Google Apps)
   [3]: https://docs.google.com (Google Docs)
   [4]: http://googlecloudprinters.laneworks.net/ (prototype of a commercial print application using google Cloud print)
   [5]: http://developer.mimeo.com/blog/blog_detail.php?ID=128 (Printing Single Sheets)
   [6]: http://developer.mimeo.com/blog/blog_detail.php?ID=129 (Printing Bound Documents)
   [7]: http://developer.mimeo.com/blog/blog_detail.php?ID=130 (Print Driver)
   [8]: http://code.google.com/apis/cloudprint/docs/overview.html (Google Cloud Print)
   [9]: http://www.mimeo.com (Mime.com)
   [10]: http://www.kinlane.com/2011/04/mimeo-cloud-printing-building-blocks/
   [11]: http://www.kinlane.com/2011/04/mimeo-connect-api-ecosystem/
   [12]: http://www.kinlane.com/2011/04/mimeo-cloud-print-vs-lulu/

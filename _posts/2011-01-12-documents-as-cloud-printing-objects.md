---
layout: post
title: "Documents as Cloud Printing Objects"
url: 'http://kinlane.com/2011/01/12/documents-as-cloud-printing-objects/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg'
---

I know very little about the [Print][1] industry. As I'm learning I find myself applying my programming and IT background to everything. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /> Currently I'm prototyping a [Cloud Print][2] platform that provides 2 step commercial [Printing][1] service from top cloud service providers:

  * [Scribd][3]
  * [Issuu][4]
  * [Amazon S3][5]
  * [Google Docs][6]
  * [Box.net][7]
  * [Dropbox][8]
When a user comes from one of these cloud providers or provides a link to their document on the [Cloud Storage][9] platform they are bringing their content with them.

I need a print object to apply to that content and create a printable document. So I am created 12 separate documents or cloud print objects to deliver common print properties such as binding, size and color. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/book-open-pages.jpg" alt="" width="250" align="right" /> Each cloud print object contains the properties most people who are printing from cloud platforms are looking for:

  * Magazine Style Binding (Saddle Stitch)
  * Book Style Binding (Perfect Bound)
  * Reporting Style Binding (Spiral Binding)
  * 8.5 X 11 Print Size (Letter)
  * 5 X 8 Print Size (A5)
  * Color or Black and White
I'm enjoying defining these different objects for use in cloud printing. These are my basic bound document definitions, I will be defining more single sheet, flyer and large format cloud print objects like posters next.

   [1]: http://www.kinlane.com/category/publishing/
   [2]: http://www.kinlane.com/category/cloud-computing/cloud-print/
   [3]: http://www.scribd.com/
   [4]: http://issuu.com/
   [5]: http://www.kinlane.com/category/amazon/amazon-s3/
   [6]: http://www.kinlane.com/category/google/google-docs/
   [7]: http://www.box.net
   [8]: http://www.dropbox.com/
   [9]: http://www.kinlane.com/category/cloud-computing/cloud-storage/

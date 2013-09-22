---
layout: post
title: "Google Storage for Developers Interoperability"
url: 'http://kinlane.com/2010/09/01/google-storage-for-developers-interoperability/'
image: 'http://code.google.com/images/code_labs_logo.gif'
---

<img class="alignnone c1" title="Google-Developer-Storage" src="http://code.google.com/images/code_labs_logo.gif" alt="" align="right" />I finally got my [Google Storage for Developers][1] email invite the other day. They promised attendees of Google I/O would get them quicker, it took 3 months.

I clicked on the link in my email and requested my keys and logged into the [Google Storage Manager][2].

It has a pretty basic interface for managing your buckets and objects. Just like [Amazon S3][3].

Then I wanted to test out the interoperability of it. Google claims:

**Google Storage is interoperable with a large number of cloud storage tools and libraries that work with services such as Amazon Simple Storage Service.** So I downloaded a common [Amazon S3 PHP Class][4] and changed the request endpoints, request headers, signature identifiers, ACLs, query string parameters and used my Google developer keys.

And it work. It listed my buckets I had created through the [Google Storage Manager][5]. I am playing with more to see how I can store files and content at both Amazon S3 and Google Developer Storage.

Now to figure out what I will use [Google Storage][6] for vs. [Amazon S3][7].

   [1]: http://code.google.com/apis/storage/
   [2]: https://sandbox.google.com/storage/
   [3]: ../category/amazon/amazon-s3/
   [4]: http://code.google.com/p/amazon-s3-php-class/
   [5]: Google%20Storage%20Manager
   [6]: http://www.kinlane.com/category/google/google-storage-for-developers/
   [7]: http://www.kinlane.com/category/amazon/amazon-s3/

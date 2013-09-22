---
layout: post
title: "File Version Control in the Clouds"
url: 'http://kinlane.com/2010/06/25/file-version-control-in-the-clouds/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

<img class="alignnone c1" title="Amazon S3" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="282" height="187" align="right" />I was just talking about using [Amazon for backing up your data in the clouds][1]. One feature that Amazon introduced recently was version control for [Amazon S3][2] data.

You can use Amazon S3 versioning to preserve, retrieve, and restore every version of every object stored in your Amazon S3 bucket. This allows you to easily recover from both unintended user actions and application failures. By default, requests will retrieve the most recently written version. Older versions of an object can be retrieved by specifying a version in the request. Storage rates apply for every version stored.

Both [Jungle Disk][3] and [Zmanda][4] offer flexible solutions where you can backup entire data sets or perform a more real-time data syncing. If your syncing data from various locations, Amazon S3 file version control may help to keep track of all changes made to files, images, video and anything you store at Amazon S3

   [1]: http://www.kinlane.com/2010/06/small-business-backup-and-recover-in-the-amazon-cloud/
   [2]: http://www.kinlane.com/category/amazon/amazon-s3/
   [3]: https://www.jungledisk.com/
   [4]: http://www.zmanda.com/cloud-backup.html

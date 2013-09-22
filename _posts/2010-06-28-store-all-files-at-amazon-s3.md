---
layout: post
title: "Store All Files at Amazon S3"
url: 'http://kinlane.com/2010/06/28/store-all-files-at-amazon-s3/'
image: 'http://kinlane-productions.s3.amazonaws.com/filetypes-2.png'
---

[Amazon S3][1] [cloud storage][2] has changed the way I manage files on my networks. I am centralizing all file storage across my web site and applications to Amazon S3. All heavy file types: <img class="c1" title="Amazon S3 File Storage" src="http://kinlane-productions.s3.amazonaws.com/filetypes-2.png" alt="" width="282" height="187" align="right" />

  * .jpg
  * .gif
  * .png
  * .tif
  * .doc / .docx
  * .xls / .xlsx
  * .fla
  * .pdf
  * .vcs
  * .zip
Should all be stored in central buckets that reflect a project client tenancy structure. Each server has a mapped network drive of **F:** to proper file bucket.

All images will be referred to using http://file.clientdomain.com.

<img class="c1" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="282" height="187" align="right" />All developers, project managers and clients can connect to each file store using:

  * FTP
  * Firefox [S3Fox][3]
  * Mapped network drive using [Jungle Disk][4]
This will take all files out of the general population on servers. Web file version control will run faster and we can access files centrally across all servers. Then files will :
  * Exist centrally, independent of any permanent or temporary [Amazon EC2][5] instance
  * Take advantage of [Amazon S3][6] versioning
  * Take advantage of [Amazon S3][1] Cloudfront regional distribution
Managing files across hundreds of projects, clients, developers, and users isn't easy. Centralizing them at Amazon S3 and backing up to another cloud provider for backups makes things more manageable.

   [1]: ../category/amazon/amazon-s3/
   [2]: http://www.kinlane.com/2010/06/cloud-storage-api-standard/
   [3]: https://addons.mozilla.org/en-US/firefox/addon/3247/
   [4]: https://www.jungledisk.com/
   [5]: http://www.kinlane.com/category/amazon/amazon-ec2/
   [6]: http://www.kinlane.com/category/amazon/amazon-s3/

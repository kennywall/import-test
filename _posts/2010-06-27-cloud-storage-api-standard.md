---
layout: post
title: "Cloud Storage API Standard"
url: 'http://kinlane.com/2010/06/27/cloud-storage-api-standard/'
image: 'http://kinlane-productions.s3.amazonaws.com/cloud.jpeg'
---

<img class="alignnone c1" title="Cloud Storage" src="http://kinlane-productions.s3.amazonaws.com/cloud.jpeg" border="1" alt="" width="250" align="right" />I was reviewing a [cloud backup product][1], [CloudBerry Backup][2] yesterday. Each time I try a new cloud storage product I can't help think how we need interroperability between all the cloud storage providers.

I would like to see a single client that could work with different cloud storage providers. Andy from Cloudberry points out this is difficult because of different approaches to cloud storage and the way their APIs work.

A standard for cloud storage is needed. _**Is Amazon S3 already the standard for cloud storage?**_ Many of the well known elements of the [Amazon S3 API][3] are:

  * RESTful Interface
  * Buckets
  * Objects
  * ACL
Several other providers have already given Amazon's API the nod as the standard, even [Google cites this under cloud storage interoperability][4]. [Dunkel cloud storage in Germany][5] even claims that they are Amazon S3 storage compliant.

With a common standard it would be easy for cloud storage clients to offer a diverse amount of storage providers, all you would have to do is change the request endpoint (URI) and your data would route to your preferred provider.

   [1]: http://www.kinlane.com/2010/06/cloud-storage-with-cloudberry-backup/
   [2]: http://cloudberrylab.com/default.aspx?page=cloudberry-backup
   [3]: http://developer.amazonwebservices.com/connect/entry.jspa?externalID=123
   [4]: http://code.google.com/apis/storage/docs/developer-guide.html
   [5]: http://www.dunkel.de/s3/

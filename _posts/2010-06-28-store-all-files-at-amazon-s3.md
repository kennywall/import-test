---
layout: post
title: Store All Files at Amazon S3
url: http://apievangelist.com/2010/06/28/store-all-files-at-amazon-s3/
source: http://apievangelist.com/2010/06/28/store-all-files-at-amazon-s3/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/filetypes-2.png
---
{% include JB/setup %}<p>Amazon S3 cloud storage has changed the way I manage files on my networks. I am centralizing all file storage across my web site and applications to Amazon S3. All heavy file types:


	.jpg
	.gif
	.png
	.tif
	.doc / .docx
	.xls / .xlsx
	.fla
	.pdf
	.vcs
	.zip

Should all be stored in central buckets that reflect a project client tenancy structure. Each server has a mapped network drive of F: to proper file bucket.
All images will be referred to using http://file.clientdomain.com.
All developers, project managers and clients can connect to each file store using:

	FTP
	Firefox S3Fox
	Mapped network drive using Jungle Disk

This will take all files out of the general population on servers. Web file version control will run faster and we can access files centrally across all servers. Then files will :

	Exist centrally, independent of any permanent or temporary Amazon EC2 instance
	Take advantage of Amazon S3 versioning
	Take advantage of Amazon S3 Cloudfront regional distribution

Managing files across hundreds of projects, clients, developers, and users isn't easy. Centralizing them at Amazon S3 and backing up to another cloud provider for backups makes things more manageable.</p>
<center><p><a href="http://apievangelist.com/2010/06/28/store-all-files-at-amazon-s3/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

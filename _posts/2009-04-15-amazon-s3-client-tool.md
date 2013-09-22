---
layout: post
title: "Amazon S3 Client Tool"
url: 'http://kinlane.com/2009/04/15/amazon-s3-client-tool/'
image: ''
---

I am constantly looking for better tools to manage my cloud environments. I have been using Amazon S3 since it first came out. I really saw the potential Amazon S3 had early on, as storage for all my web applications.

I ran a web application development company with my now ex-wife for eight years called Original Web Solutions. We were on version 4.0 of our content management system when we dissolved the company. Version 4.0 was a completely SaaS based system and utilized Amazon S3 for all heavy lifting storage. I put all images, PDF's, videos, word docs, etc. up on Amazon S3. An application was purely made of just HTML / CSS / JavaScript pages with a PHP / MySQL backend.

I also store all my data at Amazon S3 for my personal and business use. I have used [Firefox Add-On S3 Fox][1] to upload and download all my data. It has worked very well to meet my needs, except it fails a lot. It doesn't handle large files very well, and doesn't recover from poor connection failures. Its crude, but gets the job done.

For the most part I rely on writing custom code to upload files to Amazon S3.

I came across a new tool that I would put into my [professional or enterprise quality tool set for managing my Amazon S3 data][2]. It is called [CloudBerry][2].

It works like most familiar FTP clients with your local files on the left...and your remote files on the left. It is definitely the best tool out there for the average person to manage their data in the cloud.

It opens up the Amazon S3 storage cloud for use beyond just developers. I am uploading a 2.1 GB zipped folder of images right now. It is a little slower than S3 Fox or code I would write, but its slow and steady. I have to pack up my computer and go upstairs, so I will hit pause...and restart once I set back up.

I highly recommend it for those of you who wish to [start using the cloud for your every day storage needs][2].

   [1]: https://addons.mozilla.org/en-US/firefox/addon/3247
   [2]: http://cloudberrylab.com/

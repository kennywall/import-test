---
layout: post
title: File Version Control in the Clouds
url: http://kinlane.com/2010/06/25/file-version-control-in-the-clouds/
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}
I was just talking about using Amazon for backing up your data in the clouds. One feature that Amazon introduced recently was version control for Amazon S3 data.
You can use Amazon S3 versioning to preserve, retrieve, and restore every  version of every object stored in your Amazon S3 bucket.  This allows  you to easily recover from both unintended user actions and application  failures.  By default, requests will retrieve the most recently written  version.  Older versions of an object can be retrieved by specifying a  version in the request.  Storage rates apply for every version stored.
Both Jungle Disk and Zmanda offer flexible solutions where you can backup entire data sets or perform a more real-time data syncing. If your syncing data from various locations, Amazon S3 file version control may help to keep track of all changes made to files, images, video and anything you store at Amazon S3
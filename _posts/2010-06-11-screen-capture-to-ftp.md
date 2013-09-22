---
layout: post
title: "Screen Capture to FTP"
url: 'http://kinlane.com/2010/06/11/screen-capture-to-ftp/'
image: 'http://kinlane-productions.s3.amazonaws.com/spgrab.PNG'
---

I was just test driving the [Free Screenshot Sharing Application][1] called [SPGrab][1]. I like the idea of seamless sharing after you take a screenshot. They allow you to automatically upload to FTP location of your choice. Putting it in a ftp location you potentially have the ability to automatically share it.<img class="alignnone c1" title="SPGrab Screencapture" src="http://kinlane-productions.s3.amazonaws.com/spgrab.PNG" alt="" width="250" align="right" />

I spend a lot of time uploading screenshots to a Google Doc, Worpdress Blog or orther online tool. Having it automatically available at a public IP address or domain is valuable.

I might be a little different than other users, but I immediately upload all my screenshots to Amazon S3 using my S3Fox tool I like all my images to be server independent and stored in a central location I know isn't going away and I can control access. Amazon S3 gives me this control.

That would be a great feature [SPGrab][1], automatically uploading to the Amazon S3 Bucket of my choice.

   [1]: http://www.spgrab.com/

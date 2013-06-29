---
layout: post
title: A Wearable Camcorder and Community Site for Publishing
url: http://kinlane.com/2008/02/01/a-wearable-camcorder-and-community-site-for-publishing/
image: http://aws.typepad.com/photos/uncategorized/2008/01/30/vholdr_camera.jpg
---
{% include JB/setup %}
Check this cool camera out. Itis a company of action sports enthusiasts and media professionalsIt is perfect for the person who wants to document their active life.Supposively the quality is pretty good.  The camera can record 2 full hours of video on an embedded MicroSD card.  There's also a microphone built-in.Once the recording is complete, it can be uploaded to the VholdR site, tagged, labeled, and then shared.What is also very cool is the application uses several Amazon Web Services behind the scenes. All of the videos are stored in Amazon S3, and the entire EC2-powered uploading, transcoding, and post-processing system is driven by data stored in a couple of Amazon SQS instances.I'm going to have to test run one of these.
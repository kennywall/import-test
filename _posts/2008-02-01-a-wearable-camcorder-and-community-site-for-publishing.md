---
layout: post
title: "A Wearable Camcorder and Community Site for Publishing"
url: 'http://kinlane.com/2008/02/01/a-wearable-camcorder-and-community-site-for-publishing/'
image: 'http://aws.typepad.com/photos/uncategorized/2008/01/30/vholdr_camera.jpg'
---

[<img alt="Vholdr_camera" title="Vholdr_camera" src="http://aws.typepad.com/photos/uncategorized/2008/01/30/vholdr_camera.jpg" class="c1" border="0" />][1]Check this cool camera out. Itis a company of action sports enthusiasts and media professionals

It is perfect for the person who wants to document their active life.

Supposively the quality is pretty good. The camera can record 2 full hours of video on an embedded MicroSD card. There's also a microphone built-in.

Once the recording is complete, it can be uploaded to the [VholdR site][2], tagged, labeled, and then shared.

What is also very cool is the application uses several Amazon Web Services behind the scenes. All of the videos are stored in [Amazon S3][3], and the entire [EC2][4]-powered uploading, transcoding, and post-processing system is driven by data stored in a couple of [Amazon SQS][5] instances.

I'm going to have to test run one of these.

   [1]: http://www.vholdr.com/shoot/camera/overview
   [2]: http://www.vholdr.com/videolist
   [3]: http://aws.amazon.com/s3
   [4]: http://aws.amazon.com/ec2
   [5]: http://aws.amazon.com/sqs

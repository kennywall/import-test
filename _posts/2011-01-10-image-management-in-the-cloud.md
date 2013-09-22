---
layout: post
title: "Image Management in the Cloud"
url: 'http://kinlane.com/2011/01/10/2517/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

<img src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />I am taking some time and writing down my image management strategy to share with [Audrey][1]. I have a specific process and set of tools I use to manage images I use across my [Kin Lane Blog][2], [API Evangelist Blog][3] and my Twitter, LinkedIn, Facebook and other online properties.

I store all my images centrally at [Amazon S3][4]. This may not be an ideal solution for everyone, but it works for me. Its a complete storage area for all my images, audio, video and other documents.

I use a combination of [Amazon Console][5], [S3Fox for Firefox][6], [Cyberduck][7] and [Jungle Disk][8] to manage my Amazon S3 files. No time to explain the madness, it just works.

I have a central bucket at Amazon S3 for storing ALL images I need to support my public online properties. I have set a bucket policy for this bucket enforcing that all objects within are automatically publicly available. This saves me time in having to set the ACL for each object.

When I have a screenshot or creative commons image that I have found that I need to use in my blog I download, crop, resize, download and rename. Then I immediately upload to my Amazon S3 public bucket, and then copy the location to my clipboard.

With the URL of the image on Amazon S3 I go back to Wordpress and paste the URL in my blog content as an image.

Amazon S3 in conjunction with S3Fox, Cyberduck, Jungle Disk and this process allows me to store ALL images I need for my public work in a central location that I own.

My Amazon Web Services account is the center of my cloud storage world. It is important that I store all my vital files here. In the future I know where to find them and won't lost any valuable images I've used in content I have created.

   [1]: http://www.audreywatters.com
   [2]: http://www.kinlane.com
   [3]: http://www.apievangelist.com/
   [4]: http://www.kinlane.com/category/amazon/amazon-s3/
   [5]: https://console.aws.amazon.com
   [6]: https://addons.mozilla.org/en-US/firefox/addon/3247/
   [7]: http://cyberduck.ch/
   [8]: https://www.jungledisk.com/

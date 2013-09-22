---
layout: post
title: "Adding Methods to my Amazon EC2 Object"
url: 'http://kinlane.com/2010/08/23/adding-methods-to-my-amazon-ec2-object/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

<img class="alignnone c1" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />I am needing more programmatic control over my [Amazon EC2][1] environment. I am rebuilding all server instances on my Amazon Web Services network.

I needed to reconfigure using EBS Volumes for file and data storage, and upgrade the operating systems and some applications while I'm at it.

So I'm creating all new AMI as well as reconfiguring my snapshot strategy. The central object I use for programmatic manipulation of Amazon was limited.

I need to add some methods for managing the Amazon EC2 Volumes:

  * CreateVolume
  * DescribeVolumes
  * AttachVolume
  * DetachVolume
  * DeleteVolume
I'm going to need to automate the create of snapshots as well, so I added the following methods:
  * CreateSnapshot
  * DescribeSnapshots
  * DescribeSnapshotAttribute
  * DeleteSnapshot
This will give me additional control beyond just creating and managing instances. With my new EBS framework I have more granular control over different file and data stores for taking snapshots, etc.

With this more granular control over drives and their files and data, plus I was just able to offload a lot of "heavy files" like audio, flash, pdf, images, etc. [storing all the files at Amazon S3][2].

   [1]: http://www.kinlane.com/category/amazon/amazon-ec2/
   [2]: http://www.kinlane.com/2010/06/store-all-files-at-amazon-s3/

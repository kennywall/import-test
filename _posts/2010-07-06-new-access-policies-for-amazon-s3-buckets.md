---
layout: post
title: "New Access Policies for Amazon S3 Buckets"
url: 'http://kinlane.com/2010/07/06/amazon-web-services-releases-more-granular-access-policies-for-amazon-s3-buckets/'
image: 'http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg'
---

[<img class="alignnone c1" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="282" height="187" align="right" />][1][Amazon Web Services released support for Bucket Policies within Amazon S3 Cloud Storage today][2]. [Bucket policies][3] provide access control management for Amazon S3 buckets and for the objects in them using a single unified mechanism. The policies are expressed using whats called Access Policy Language, that enables centralized management of permissions.

Access Control Lists (ACLs) can only be used to grant permissions on individual objects, policies can either add or deny permissions across all of the objects within a single bucket. You can use regular expression operators, so that you can control access to groups that begin with a common prefix or end with a specific file extension such as ".pdf, word, or .html documents

Policies can include references to:

  * IP addresses
  * IP address ranges in CIDR notation
  * Dates
  * User Agents
  * HTTP referrer
  * http and https
<img class="alignnone c2" title="Amazon S3 Bucket" src="http://kinlane-productions.s3.amazonaws.com/bucket.jpg" alt="" width="250" align="right" />This really gives me much more granular level control over Amazon S3 buckets. I was just having problems with [storing all my server files centrally at Amazon S3][4] because I couldn't establish settings for entire buckets. I have been distracted by other work lately and with the Fourth of July holiday. Now I can set up a bucket policy to:

  * Allow Comprehensive Write Access
  * Access from Specific Networks
  * Allow Access from Specific Application using User Agent
I am reviewing my file management policies for [Amazon S3][5] right now to see how I can create different levels of access. This will definitely make it easier for me to require all workstations, servers and web applications to store ALL files in [Amazon S3][5] Buckets.

   [1]: http://aws.amazon.com/
   [2]: http://aws.typepad.com/aws/2010/07/amazon-s3-bucket-policies-another-way-to-protect-your-content.html
   [3]: http://docs.amazonwebservices.com/AmazonS3/latest/dev/index.html?UsingBucketPolicies.html
   [4]: http://www.kinlane.com/2010/06/store-all-files-at-amazon-s3/
   [5]: http://www.kinlane.com/category/amazon/amazon-s3/

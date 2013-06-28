---
layout: post
title: Amazon Web Services Offers Server Side Encryption for Amazon S3
url: http://apievangelist.com/2011/10/05/amazon-web-services-offers-server-side-encryption-for-amazon-s3/
source: http://apievangelist.com/2011/10/05/amazon-web-services-offers-server-side-encryption-for-amazon-s3/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/amazon/amazon-s3-encryption.png
---
{% include JB/setup %}<p>Amazon Web Services now offers Server Side Encryption (SSE) for Amazon S3, enablingthe ability to encrypt data stored in Amazon S3, by adding an additional request header when writing the object to Amazon S3, with decryptionoccurringautomatically when data is retrieved.Amazon S3 Server Side Encryption employs multi-factor encryption, with each object encrypted with a unique key, and as an additional safeguard, this key is itself encrypted with a regularly rotated master key.Amazon S3 Server Side Encryption uses one of the strongest block ciphers available -- 256-bit Advanced Encryption Standard (AES-256).You can start using Amazon S3 Server Side Encryption in the AWS Management Console:

	Under the Amazon S3 tab, use the upload dialog to add files to be uploaded.In the Set Details section of the upload dialog, set the Use Server Side Encryption checkbox property.</p>
<center><p><a href="http://apievangelist.com/2011/10/05/amazon-web-services-offers-server-side-encryption-for-amazon-s3/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

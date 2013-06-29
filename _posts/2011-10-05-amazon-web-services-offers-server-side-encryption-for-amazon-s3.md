---
layout: post
title: Amazon Web Services Offers Server Side Encryption for Amazon S3
url: http://kinlane.com/2011/10/05/amazon-web-services-offers-server-side-encryption-for-amazon-s3/
image: http://kinlane-productions.s3.amazonaws.com/amazon/amazon-s3-encryption.png
---
{% include JB/setup %}

Amazon S3 Server Side Encryption employs multi-factor encryption, with each object encrypted with a unique key, and as an additional safeguard, this key is itself encrypted with a regularly rotated master key. Amazon S3 Server Side Encryption uses one of the strongest block ciphers available -- 256-bit Advanced Encryption Standard (AES-256).
You can start using Amazon S3 Server Side Encryption in the AWS Management Console:

	Under the Amazon S3 tab, use the upload dialog to add files to be uploaded.
	In the Set Details section of the upload dialog, set the Use Server Side Encryption checkbox property.
	Start Upload. The files will be encrypted and stored in Amazon S3.

If you prefer to manage your own encryption keys, you can also make use of the client libraries for encryption provided by Amazon. To learn more, visit the Amazon S3 Encryption client page.
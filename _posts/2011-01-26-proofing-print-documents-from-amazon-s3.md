---
layout: post
title: Proofing Print Documents From Amazon S3
url: http://kinlane.com/2011/01/26/proofing-print-documents-from-amazon-s3/
image: http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg
---
{% include JB/setup %}
<p>
     I am making my way through each major cloud storage provider and building demos that pull PDF files from the provider and proofs the file before printing with Mimeo. I have put together a demonstration of how to pull a PDF file from Amazon S3 and the proof it with Mimeo Connect. You will need: Amazon Web Services Account Mimeo API Account. This Cloud Print demonstration is written in PHP, and uses the Mimeo Connect Cloud Print API REST Client. You can download the source code for the Amazon S3 to Mimeo Connect project in the following formats: git (GitHub Repository) - Amazon S3 to Mimeo Print svn (Google Code Project - Amazon S3 to Mimeo Print I will be updating this project when I develop any new code that integrates Amazon S3 and the Mimeo Connect Cloud Print API. This project currently allows you to pull print files from Amazon S3 and proof them with Mimeo Connect Cloud Print API and preview or view any pages in the PDF as images in Flash or JQuery Flipbook.
</p>
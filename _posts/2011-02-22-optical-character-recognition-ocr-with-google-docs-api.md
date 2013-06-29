---
layout: post
title: Optical Character Recognition OCR with Google Docs API
url: http://kinlane.com/2011/02/22/optical-character-recognition-ocr-with-google-docs-api/
image: http://kinlane-productions.s3.amazonaws.com/mimeo/PDF-OCR.png
---
{% include JB/setup %}
<p>
     Using the Google Docs List API you can convert high-resolution PDFs or images into editable text using Optical Character Recognition (OCR). Google Docs List API can extract the text from the following document formats: PDF Document (application/pdf) JPG Image (image/jpeg) PNG Image (image/png) GIF Image (image/gif) OCR is an experimental API feature and has a quota in place, limiting the number of calls that can be made. API quota is higher for Google Apps for Business users. OCR is available through the API by including the ocr=true parameter when uploading a file, then produces a separate Google Docs with extracted text for each uploaded PDF or Image.
</p>
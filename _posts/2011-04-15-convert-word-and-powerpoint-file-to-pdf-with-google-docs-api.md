---
layout: post
title: "Convert Word and Powerpoint File to PDF with Google Docs API"
url: 'http://kinlane.com/2011/04/15/convert-word-and-powerpoint-file-to-pdf-with-google-docs-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/word-to-pdf-conversion.gif'
---

I'm slowly packaging up all the code I've been writing lately for [Google Docs Listing API][1].

I am building quite a few bite size modules that do various things with Google Docs.

Today I cleaned up a piece of PHP code that will upload file to Google Docs using API, then export various file types.

If it is a .doc file, it will convert to:<img src="http://kinlane-productions.s3.amazonaws.com/word-to-pdf-conversion.gif" alt="" width="200" align="right" />

  * .pdf
  * .png
  * .swf
  * .txt
  * .html
If it is a .ppt file, it will convert to:<img src="http://kinlane-productions.s3.amazonaws.com/powerpoint-to-pdf.png" alt="" width="150" align="right" />
  * .pdf
  * .png
  * .swf
  * .txt
This code is a stripped down version of the [Zend - Google Docs API PHP language library][2], and requires the [Zend Gdata Library][3] to run.

   [1]: http://code.google.com/apis/documents/ (Google Docs Listing API)
   [2]: http://code.google.com/apis/documents/docs/1.0/developers_guide_php.html (Zend - Google Docs API PHP Language Library)
   [3]: http://framework.zend.com/manual/en/zend.gdata.docs.html (Zend GData Library)

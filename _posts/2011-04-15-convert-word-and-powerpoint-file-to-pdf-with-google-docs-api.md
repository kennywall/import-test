---
layout: post
title: Convert Word and Powerpoint File to PDF with Google Docs API
url: http://kinlane.com/2011/04/15/convert-word-and-powerpoint-file-to-pdf-with-google-docs-api/
image: http://kinlane-productions.s3.amazonaws.com/word-to-pdf-conversion.gif
---
{% include JB/setup %}
<p>
     I'm slowly packaging up all the code I've been writing lately for Google Docs Listing API. I am building quite a few bite size modules that do various things with Google Docs. Today I cleaned up a piece of PHP code that will upload file to Google Docs using API, then export various file types. If it is a .doc file, it will convert to: .pdf .png .swf .txt .html If it is a .ppt file, it will convert to: .pdf .png .swf .txt This code is a stripped down version of the Zend - Google Docs API PHP language library, and requires the Zend Gdata Library to run.
</p>
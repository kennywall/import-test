---
layout: post
title: "Google Docs File Size Limitations"
url: 'http://kinlane.com/2011/02/22/google-docs-file-size-limitations/'
image: 'http://kinlane-productions.s3.amazonaws.com/google/google-docs-icon.jpg'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/google/google-docs-icon.jpg" alt="" width="200" align="right" />I spent some time this evening researching file size limitations for Google Docs. Here is what I found:

  * **Documents** \- 512,000 characters, regardless of the number of pages or font size. Uploaded document files that are converted to Google documents format can't be larger than 1MB.
  * **Spreadsheets** \- Uploaded spreadsheet files that are converted to Google spreadsheets format can't be larger than 20MB, and need to be under 400,000 cells and 256 columns per sheet.
  * **Presentations**: - Presentations created in Google Docs can be up to 10MB -- which is about 200 slides.
  * **Drawings** \- There is no document size limitation posted.
One thing I did not know was that files you upload, but do not convert to Google Doc format can be up to [1GB][1] in size.

I have been concerned with using Google Docs as primary cloud storage because I always seem to be getting yelled at for file size too large on upload. However I'm always converting file at upload.

1GB is plenty big for any file I will be storing in the clouds. If I need bigger I can use Amazon S3.

   [1]: http://en.wikipedia.org/wiki/Gigabyte (Gigabyte)

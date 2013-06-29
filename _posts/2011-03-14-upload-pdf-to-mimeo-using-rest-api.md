---
layout: post
title: Upload PDF to Mimeo Using REST API
url: http://kinlane.com/2011/03/14/upload-pdf-to-mimeo-using-rest-api/
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}
<p>
     I've been proofing documents with the Mimeo Connect Cloud Print API. Now I want to start just uploading print files into my Mimeo account. I added support for posting files to the Mimeo REST client. Here is a sample POST to the Mimeo Connect Cloud Print API Storage Service. Storage Service will create any folder structure you specify when posting file. All files and folders are created in the root /printfileroot folder in the specified My Mimeo account.
</p>
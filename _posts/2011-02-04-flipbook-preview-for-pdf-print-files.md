---
layout: post
title: Flipbook Preview for PDF Print Files
url: http://kinlane.com/2011/02/04/flipbook-preview-for-pdf-print-file/
image: http://kinlane-productions.s3.amazonaws.com/flipbook.jpg
---
{% include JB/setup %}
<p>
     When I am building a user interface for any print application I want to allow users to preview their PDF after upload. The Mimeo Proofing Service is what I use. Proofing takes a PDF and generates a small and large image for each page of the PDF, and adds to your Mimeo account. First I pull the PDF, and send it to the Mimeo Proofing Service, and it returns XML containing a list of all the proofed images for PDF. I created a PHP script that allows you to preview a PDF you are about to print in a flipbook format. I use the very simpleFlipbook script from Coast Works. I will be creating a smaller preview version, and probably throw it in some sort of JQuery Lightbox so it can load from the build print document interface. You can download the first version of the flip book as: git @ github - Flipbook Print Proof Preview svn @ Google Code - Flipbook Print Proof Preview
</p>
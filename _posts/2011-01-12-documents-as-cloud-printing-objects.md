---
layout: post
title: Documents as Cloud Printing Objects
url: http://kinlane.com/2011/01/12/documents-as-cloud-printing-objects/
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}
I know very little about the Print industry.  As I'm learning I find myself applying my programming and IT background to everything.

Currently I'm prototyping a Cloud Print platform that provides 2 step commercial Printing service from top cloud service providers:

	Scribd
	Issuu
	Amazon S3
	Google Docs
	Box.net
	Dropbox

When a user comes from one of these cloud providers or provides a link to their document on the Cloud Storage platform they are bringing their content with them.
I need a print object to apply to that content and create a printable document.  So I am created 12 separate documents or cloud print objects to deliver common print properties such as binding, size and color.

Each cloud print object contains the properties most people who are printing from cloud platforms are looking for:

	Magazine Style Binding (Saddle Stitch)
	Book Style Binding (Perfect Bound)
	Reporting Style Binding (Spiral Binding)
	8.5 X 11 Print Size (Letter)
	5 X 8 Print Size (A5)
	Color or Black and White

I'm enjoying defining these different objects for use in cloud printing.  These are my basic bound document definitions, I will be defining more single sheet, flyer and large format cloud print objects like posters next.
---
layout: post
title: Proofing Print Documents From Box.net
url: http://apievangelist.com/2011/02/02/proofing-print-documents-from-box-net/
source: http://apievangelist.com/2011/02/02/proofing-print-documents-from-box-net/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/box-net-logo.jpg
---
{% include JB/setup %}I am making my way through each major cloud storage provider and building demos that pull PDF files from the provider and proofs the file before printing with Mimeo.

I have put together a demonstration of how to pull a PDF file from Box.net and the proof it with Mimeo Connect.
You will need:

	Box.net Account
	Mimeo API Account.

This Cloud Print demonstration is written in PHP, and uses the Mimeo Connect Cloud Print API REST Client.

You can download the source code for the Box.netto Mimeo Connect project in the following formats:

	git (GitHub Repository) - Box.net to Mimeo Print
	svn (Google Code Project - Box.net to Mimeo Print

I will be updating this project when I develop any new code that integrates Box.net and the Mimeo Connect Cloud Print API.
This project currently allows you to pull print files from Box.net and proof them with Mimeo Connect Cloud Print API and preview or view any pages in the PDF as images in Flash or JQuery Flipbook.

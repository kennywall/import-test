---
layout: post
title: Mimeo Connect Print API
url: http://apievangelist.com/2010/11/07/mimeo-connect-print-api/
source: http://apievangelist.com/2010/11/07/mimeo-connect-print-api/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}I've talked about the My Mimeo online print and publishing, and the My Mimeo Marketplace where you can publish documents for people to purchase.   Now I feel I can actually introduce you to the Mimeo Connect Print API, now that you have an overview of Mimeo.
Mimeo offers a SOAP Print API as its core enterprise print offering, however my focus with Mimeo is the REST Print API.    The REST API uses basic HTTP Authentication for access your My Mimeo Account, and provides the following services:

	Account Service - Management of your My Mimeo Account(s).
	Document Service - Access and management of your Mimeo documents assembled in your My Mimeo account.
	Storage Service - File storage service for various files you use in assembling print documents.
	Proof Service - Pulling of files from external locations into your My Mimeo library.
	Order Service - Order of print documents through your My Mimeo account.
	Marketplace Service - Access, publishing and management of your My Mimeo documents to your My Mimeo Marketplaces.

Everything is based upon documents you create within your My Mimeo self-publishing interface.  You can build documents such as binders, book, flyers, posters and more using your My Mimeo account.

For example, you can create a 20 page booklet complete with cover file, 20 page content files, and a back cover file.  When building your document in My Mimeo you choose all the characteristics of your book from cover, binding, paper, color, etc.  During the process you upload three support files to provide unique content for this book.  One for cover, one for content, and one for back cover.   At any point using the Mimeo Connect REST API Proof Service you can pull new files dynamically from other locations and create new versions of your book document.
You can apply the same concept to a single sheet flyer or poster.  You would build your base document in your My Mimeo, then dynamically pull a PDF from any public location and merge with your flyer or poster document, creating an entirely new print document in real-time.
Then with the Mimeo Connect REST API Order Service you can generate an order, set how fast you want your order, and the shipping options you want.  It returns a quote that you can use to make ordering decisions from.  Then your printed document arrives on your doorstep at your selected time.
Its a pretty interesting approach to print-on-demand, self-publishing, web-to-print or what ever term you wish to use.  It allows you to build base libraries of documents and dynamically generate print orders from these documents, using files uploaded by users of your web applications.
I will be spending more time playing with the API over the coming weeks and providing more specific samples of how to build rich web and social applications that take advantage of the REST Print API.
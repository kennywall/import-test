---
layout: post
title: Mimeo Connect Cloud Print API in C#
url: http://apievangelist.com/2011/06/29/c-sharp-code-for-the-mimeo-connect-cloud-print-api/
source: http://apievangelist.com/2011/06/29/c-sharp-code-for-the-mimeo-connect-cloud-print-api/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/C-Sharp.jpg
---
{% include JB/setup %}<p>
There has been a lot of requests for .NET code samples for integrating applications with the Mimeo Connect Cloud Print API.
I was telling too many potential customers that I do not have .NET code samples, and they would have to write from scratch.
So I finally made time to cranking out a handful of core code samples in C#.  I focused the Mimeo Print Order Service first, with examples showing how to work with these five methods:

	NewProduct - Creating a new document template or shell for a new print order
	GetItemQuote - Getting a current print quote for a single print product
	GetShippingOptions - Get shipping and deliver options for an order
	GetOrderQuote - Get a complete quote for an entire print order
	PlaceOrder - Place a print order with Mimeo.com

These code samples are meant for demonstration.  So they work as is, and may not reflect best practices for a production application environment.  But they provide all the code you will need to make each call against our REST API and print on demand.
I will be working on creating more C# samples for Mimeo Connect Cloud Print API methods next like print proofing, document, account and address book management in coming weeks.
You can get at each code sample by click on the links above, or download the complete set at Github.
</p>
<center><p><a href="http://apievangelist.com/2011/06/29/c-sharp-code-for-the-mimeo-connect-cloud-print-api/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

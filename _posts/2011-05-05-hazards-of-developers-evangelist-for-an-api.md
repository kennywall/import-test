---
layout: post
title: Hazards of Developers Evangelist for an API.
url: http://kinlane.com/2011/05/05/hazards-of-developers-evangelist-for-an-api/
source: http://kinlane.com/2011/05/05/hazards-of-developers-evangelist-for-an-api/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo/mimeo_connect_logo.jpg
---
{% include JB/setup %}<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/mimeo_connect_logo.jpg" alt="" width="250" align="right" />I'm working to make it easier to get up and running using the Mimeo Connect Cloud Print API. One concept that is tough to understand at first, is that all printing starts with a Mimeo document. Then using the API you can either order that document as is, or merge one or many PDF documents with it, generate a dynamic document, then order this new document. As part of our API, we have a Document Listing Service, except it only pulls documents from a central account I have control of. So if you want to pull one of the documents you created, you have to actually pull the Document ID from your My Mimeo account. Sounds easy right? Well its available in the URL, and in a properties screen for the document. The Document ID is a GUID, for those of you who don't know what a GUID is:
<p class="c2">
     <em>A globally unique identifier or GUID (pronounced /??u??d/ or /??w?d/) is a unique reference number used as an identifier in computer software</em> <em>So a Document ID looks like this:</em>
</p>
<p class="c2">
     <em>3F2504E0-4F89-11D3-9A0C-0305E82C3301</em> Except for some reason the one that shows in My Mimeo is missing the dashes, and doesn't work when you pass through the API.
</p>So I ask my API developer, where is the easiest place to get the Document ID? He says, "In the URL or as property of document". I explain it doesn't work without dashes. His response is, Developers will understand, and know to put dashes back in. And that is a hazard of putting developers as the public face of your API. They make a lot of assumptions based upon what they know. API Evangelists and developer advocates should definitely have programming skills, but ideally they should have a balance of proramming, business and marketing skills.
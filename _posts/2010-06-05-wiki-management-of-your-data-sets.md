---
layout: post
title: Wiki Management of Your Data Sets
url: http://apievangelist.com/2010/06/05/wiki-management-of-your-data-sets/
source: http://apievangelist.com/2010/06/05/wiki-management-of-your-data-sets/
domain: apievangelist.com
image: 
---
{% include JB/setup %}I was reviewing the Google Sites API today. I have a Google Site / Wiki that I was maintaining last year about cloud computing. Like other side projects of mine that don't directly have funding it fell to the wayside, however I've been still bookmarking and gathering relevant data that still applies to this Cloud Computing Wik. I would like to find a way to refresh it.
Google  Sites API and Google Docs API provide a great way to programmatically generate either private or public collections of your data. It can generate sites on fly and build out complete information architectures based upon whatever the data sets are. Within a site you can:

	Create Pages and SubPages
	Upload Files
	Update Content
	Delete Content

Once a site is generated you can control the ACL of the site if you wish to keep the content private and accessible only by specific people. Or you can make completely public.
After site is up you can also programatically access the activity within the site through harvesting of comments, files and other content changes made by users.
For my cloud computing wiki model I wanted the entire main site to remain free. However I wanted granular control over specific research documents and white papers. Either because I don't want them generally available or because I want to charge for access.
I chose to use Google Docs for this. I can easily generate docs, spreasheets, and PDFs that have title and brief description on pages and then offer request form or Google Checkout link to pay for access. Once access is granted I can easily turn on file sharing for a specific user to that document.
Some great tools for creating wikis to manage your various data collections, sets, and research projects. It can be generated from your existing database and allow you to control who has access and can help curate.
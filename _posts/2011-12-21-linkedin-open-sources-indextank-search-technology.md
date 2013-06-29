---
layout: post
title: LinkedIn Open Sources IndexTank Search Technology
url: http://kinlane.com/2011/12/21/linkedin-open-sources-indextank-search-technology/
image: http://kinlane-productions.s3.amazonaws.com/linkedin/LinkedIn-Developer-Network.png
---
{% include JB/setup %}

The IndexTank technology has three separate toolsets:

	IndexEngine - A real-time fulltext search-and-indexing system designed to separate relevance signals from document text
	API - A RESTful interface that handles authentication, validation, and communication with the IndexEngine(s)
	Nebulizer - Multitenant framework to host and manage an unlimited number of indexes running over a layer of Infrastructure-as-a-Service

 An example of IndexTank in action is, Reddit, which runs on IndexEngine and the API.
They have the IndexTank Engine and IndexTank Service code published at Github, and created a LinkedIn Group to support it.
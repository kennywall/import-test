---
layout: post
title: "The Gliffy Diagram API"
url: 'http://kinlane.com/2011/07/14/the-gliffy-diagram-api/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist/gliffy/gliffy-logo.gif'
---

[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/gliffy/gliffy-logo.gif" alt="" width="150" align="right" />][1]

The [Gliffy API][2] makes it possible for developers to add Glffy diagramming software to other web applications.

The Gliffy API provides a RESTful web service and set of embeddable tools for adding flow charts, network diagrams, class diagrams and more to their wiki pages, blogs, content management systems (CMS), and sites.

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/gliffy/gliffy-api-server.jpg" alt="" width="200" align="right" />

oAuth is used authentication and there are four services available, providing access to accounts, documents, folders, and users, with all API responses in XML.

Gliffy also provides two embeddable tools for working with the Gliffy API:

  * **Diagram Editor** \- Embedding of Gliffy diagram editor in any web application.
  * **Diagram Videwer** \- Displays a copy of diagram in JPEG or PNG format.
Gliffy stores all documents in their company data center, with plans to allow storage elsewhere in the future.

You can build a set of diagrams using the Gliffy web application, and pull these drawings using the [Gliffy API][3]. Then make available for wiki pages, blogs, articles, presentations and other sites. Or, you can just embed the editor and let users create their own drawings.

   [1]: http://www.gliffy.com
   [2]: http://www.gliffy.com/products/online/api/ (Gliffy API)
   [3]: http://developer.mimeo.com/community/application_detail.php?ID=26 (Gliffy API)

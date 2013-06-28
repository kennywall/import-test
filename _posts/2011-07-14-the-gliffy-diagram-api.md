---
layout: post
title: The Gliffy Diagram API
url: http://kinlane.com/2011/07/14/the-gliffy-diagram-api/
source: http://kinlane.com/2011/07/14/the-gliffy-diagram-api/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist/gliffy/gliffy-logo.gif
---
{% include JB/setup %}

<p>
     <a href="http://www.gliffy.com" target="_blank"><img class="c1" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/gliffy/gliffy-logo.gif" alt="" width="150" align="right" /></a> The <a title="Gliffy API" href="http://www.gliffy.com/products/online/api/">Gliffy API</a> makes it possible for developers to add Glffy diagramming software to other web applications. The Gliffy API provides a RESTful web service and set of embeddable tools for adding flow charts, network diagrams, class diagrams and more to their wiki pages, blogs, content management systems (CMS), and sites. <img class="c1" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/gliffy/gliffy-api-server.jpg" alt="" width="200" align="right" /> oAuth is used authentication and there are four services available, providing access to accounts, documents, folders, and users, with all API responses in XML. Gliffy also provides two embeddable tools for working with the Gliffy API:
</p>
<ul class="blue">
     <li>
          <strong>Diagram Editor</strong> - Embedding of Gliffy diagram editor in any web application.
     </li>
     <li>
          <strong>Diagram Videwer</strong> - Displays a copy of diagram in JPEG or PNG format.
     </li>
</ul>
<p>
     Gliffy stores all documents in their company data center, with plans to allow storage elsewhere in the future. You can build a set of diagrams using the Gliffy web application, and pull these drawings using the <a title="Gliffy API" href="http://developer.mimeo.com/community/application_detail.php?ID=26">Gliffy API</a>. Then make available for wiki pages, blogs, articles, presentations and other sites. Or, you can just embed the editor and let users create their own drawings.
</p>
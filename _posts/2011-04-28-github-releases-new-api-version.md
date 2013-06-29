---
layout: post
title: Github Releases New API Version
url: http://kinlane.com/2011/04/28/github-releases-new-api-version/
image: http://kinlane-productions.s3.amazonaws.com/github/github-round.png
---
{% include JB/setup %}
<p>
     Github has released version 3.0 of their API. Using the new Github API users canmanage labels, issue comments, milestones, and events. The new API also has full support for Gists. They've also made several updates to their RESTful approach: URLs are simpler and more consistent: https://api.github.com/repos/github/gollum/issues.json. Resources return url fields so that clients don't have to build URLs. Create/Update actions take JSON, instead of POST parameters. Pagination and Rate Limiting info is returned on every applicable request. JSON-P requests get a special payload with header information. The new version of the API only supports JSON as the request and response format. There is also a new daily cap of 5000 requests for the API. There are still supporting API v2, and will announce deprecation plans soon.
</p>
---
layout: post
title: "Github Releases New API Version"
url: 'http://kinlane.com/2011/04/28/github-releases-new-api-version/'
image: 'http://kinlane-productions.s3.amazonaws.com/github/github-round.png'
---

<img src="http://kinlane-productions.s3.amazonaws.com/github/github-round.png" alt="" width="200" align="right" />[Github][1] has [released version 3.0 of their API][2].

Using the new [Github API][3] users canmanage labels, issue comments, milestones, and events.

The new API also has full support for [Gists][4].

They've also made several updates to their RESTful approach:

  * URLs are simpler and more consistent: https://api.github.com/repos/github/gollum/issues.json.
  * Resources return url fields so that clients don't have to build URLs.
  * Create/Update actions take JSON, instead of POST parameters.
  * Pagination and Rate Limiting info is returned on every applicable request.
  * JSON-P requests get a special payload with header information.
The new version of the API only supports JSON as the request and response format.

There is also a new daily cap of 5000 requests for the API.

There are still supporting API v2, and will announce deprecation plans soon.

   [1]: https://github.com/ (Github)
   [2]: https://github.com/blog/846-new-issues-and-gist-api (released version 3.0 of their API)
   [3]: http://developer.github.com/v3/ (Github API)
   [4]: https://gist.github.com/ (Gists)

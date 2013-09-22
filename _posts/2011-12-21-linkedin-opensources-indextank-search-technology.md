---
layout: post
title: "LinkedIn Open-Sources IndexTank Search Technology"
url: 'http://kinlane.com/2011/12/21/linkedin-open-sources-indextank-search-technology/'
image: 'http://kinlane-productions.s3.amazonaws.com/linkedin/LinkedIn-Developer-Network.png'
---

<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/linkedin/LinkedIn-Developer-Network.png" alt="" width="175" align="right" />[LinkedIn has just open-sourced the technology behind IndexTank][1] under the Apache 2.0 License.

The IndexTank technology has three separate toolsets:

  * **IndexEngine** \- A real-time fulltext search-and-indexing system designed to separate relevance signals from document text
  * **API** \- A RESTful interface that handles authentication, validation, and communication with the IndexEngine(s)
  * **Nebulizer** \- Multitenant framework to host and manage an unlimited number of indexes running over a layer of Infrastructure-as-a-Service
[<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/indextank/indextank_logo.png" alt="" width="250" align="right" />][2] An example of IndexTank in action is, Reddit, which runs on IndexEngine and the API.

They have the [IndexTank Engine][3] and [IndexTank Service][4] code published at Github, and created a [LinkedIn Group to support it][5].

   [1]: http://engineering.linkedin.com/open-source/indextank-now-open-source (LinkedIn has just open-sourced the technology behind IndexTank)
   [2]: http://indextank.com/
   [3]: https://github.com/linkedin/indextank-engine
   [4]: https://github.com/linkedin/indextank-service
   [5]: http://www.linkedin.com/groups?gid=4224441 (LinkedIn Group to Support It)

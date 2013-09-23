---
layout: post
title: "Continuing the Migration of Projects Over To Github"
url: 'http://kinlane.com/2013/03/21/continuing-the-migration-of-projects-over-to-github/'
image: 'http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/github-kin-lane.png'
---

[<img src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/github/github-kin-lane.png" alt="" width="150" align="right" />][1]

I’m continuing the [migration of all my projects to run on Github][2]. Eventually all public areas of my site will run as static, published Github pages and supporting back-end repositories. Last night I migrated [API aggregation][3], [Backend as a Service][4], [Reciprocity][5] and [Real-Time][6] providers using a version of my [Hacker Storytelling][7] format.

While [apievangelist.com][8] will still remain the master doorway to all my work, each project will live under its own subdomain and Github repository. As I make this switch I’m having to adjust my Google Analytics strategy as well as potentially my Google Feedburner strategy. In the shadow of the Google Reader deprecation I’m reconsidering not just how I consume RSS, but my analytics as well.

I can keep using Google Analytics for pages, and Google Feedburner for RSS. But I’d also like data on how JSON files are consumed as well, which neither platform provide me. Using the Github API I can track on the activity around a repository like commits, follows, downloads and forks, but I don’t get actually page view activity on pages or individual files.

Really my only hope for getting the data I need is from Github. Some sort of raw web logs for our domain, would be sweeeet!! Then I could see how many times a JSON file is accessed, and build custom reporting tools for Github page views, Jekyll blog views, etc and migrate away from Google Analytics.

I've looked briefly for any Github solutions, but everything is client-side tracking.  Let me know if I'm missing anything.

[<img class="c1" src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/github/github-contributions.png" alt="" width="550" />][1]

   [1]: https://github.com/kinlane
   [2]: /2013/01/02/all-side-projects-are-now-hosted-on-github/ (migration of all my projects to run on Github)
   [3]: http://aggregation.apievangelist.com/
   [4]: http://baas.apievangelist.com/
   [5]: http://reciprocity.apievangelist.com/
   [6]: http://realtime.apievangelist.com/
   [7]: http://hackerstorytelling.com
   [8]: http://apievangelist.com

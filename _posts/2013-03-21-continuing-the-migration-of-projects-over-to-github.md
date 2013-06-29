---
layout: post
title: Continuing the Migration of Projects Over To Github
url: http://kinlane.com/2013/03/21/continuing-the-migration-of-projects-over-to-github/
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/github-kin-lane.png
---
{% include JB/setup %}

I&rsquo;m continuing the migration of all my projects to run on Github.  Eventually all public areas of my site will run as static, published Github pages and supporting back-end repositories.  Last night I migrated API aggregation, Backend as a Service, Reciprocity and Real-Time providers using a version of my Hacker Storytelling format.
While apievangelist.com will still remain the master doorway to all my work, each project will live under its own subdomain and Github repository.  As I make this switch I&rsquo;m having to adjust my Google Analytics strategy as well as potentially my Google Feedburner strategy.  In the shadow of the Google Reader deprecation I&rsquo;m reconsidering not just how I consume RSS, but my analytics as well.
I can keep using Google Analytics for pages, and Google Feedburner for RSS.  But I&rsquo;d also like data on how JSON files are consumed as well, which neither platform provide me.  Using the Github API I can track on the activity around a repository like commits, follows, downloads and forks, but I don&rsquo;t get actually page view activity on pages or individual files.
Really my only hope for getting the data I need is from Github.  Some sort of raw web logs for our domain, would be sweeeet!!  Then I could see how many times a JSON file is accessed, and build custom reporting tools for Github page views, Jekyll blog views, etc and migrate away from Google Analytics.
I've looked briefly for any Github solutions, but everything is client-side tracking. &nbsp;Let me know if I'm missing anything.

---
layout: post
title: "Auto Deploy Code from Github"
url: 'http://kinlane.com/2011/03/13/3221/'
image: 'http://kinlane-productions.s3.amazonaws.com/github-logo.png'
---

<img src="http://kinlane-productions.s3.amazonaws.com/github-logo.png" alt="" width="250" align="right" />I came across a great walk through of [how to deploy your code from GitHub automatically][1].

Having managed a large number of web applications derived from various code repositories, I see the value in this.

I used to write some pretty complex scripts to do this automatically with SVN across 20 Amazon EC2 instances.

You can configure your EC2 AMIs to automatically update upon new instances launch. Great way to load-balance code.

I'm going to set this up for my 5 wordpress installs, so that they get updated when Wordpress gets update.

Good to know how to do for the future, with my other web applications.

######  Related articles

  * [Your GitHub Activity, Now Available on LinkedIn][2] (readwriteweb.com)
  * [Make GitHub part of your professional reputation][3] (linkedin.com)
  * [Rapportive (YC S10) for developers: Bitbucket, GitHub ][4]

   [1]: http://shinyplasticbag.posterous.com/how-to-deploy-your-code-from-github-automatic (How to Deploy Your Code from Github Automatically)
   [2]: http://www.readwriteweb.com/hack/2011/03/your-github-activity-now-avail.php
   [3]: http://blog.linkedin.com/2011/03/08/github-linkedin/
   [4]: http://blog.rapportive.com/rapportive-for-developers-bitbucket-github-st

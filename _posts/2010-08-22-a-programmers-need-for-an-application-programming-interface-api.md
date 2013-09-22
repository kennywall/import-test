---
layout: post
title: "A Programmers Need for an Application Programming Interface (API)"
url: 'http://kinlane.com/2010/08/22/a-programmers-need-for-an-application-programming-interface-api/'
image: 'http://www.alchemyapi.com/images/alchemyAPI.jpg'
---

I have a "hobby" harvesting project going on right now. I'm am harvesting several thousand web pages from various locations on a certain topic.

I'm not really interested in the content itself, but the top keywords that are used in the content. I pulled the page and extracted the body content that I am interested in analyzing.

I then want to pull a list of the top keywords and key phrases used in the page.

So I am faced with next steps:

  1. Spend time researching algorithms for parsing text and looking for words
  2. Write my own scripts for identifying key words and key phrases (harder than you think)
  3. Evolve and continue scripts to make more intelligent over time
<img class="alignnone c1" title="AlchemyAPI" src="http://www.alchemyapi.com/images/alchemyAPI.jpg" alt="" width="259" height="57" align="right" />There is a lot of time and money investment there. Easy to give up on my project at this point.

I start looking for existing tools or APIs that would accomplish this. I came across a great [tag, keyword, and key phrase intelligence API][1] called [AlchemyAPI][1].

They have a great API that takes content, and returns an intelligent set of tags. Now I am one more step closer to being able to [extract meaningful key phrases and tag sets][2].

It is also a great example of how good Application Programming Interface (API) can assist developers in delivering projects.

   [1]: http://www.alchemyapi.com/
   [2]: http://www.kinlane.com/2010/08/meaningful-key-phrases-and-tag-sets/

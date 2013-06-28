---
layout: post
title: The Power of Using APIs
url: http://apievangelist.com/2010/12/30/the-power-of-using-apis/
source: http://apievangelist.com/2010/12/30/the-power-of-using-apis/
domain: apievangelist.com
image: 
---
{% include JB/setup %}Here is a brief example of how APIs can quickly deliver value in every day business.
I wanted a way to evaluate the content of bookmarks using my Pinboard (anti-social) application  So I employed the Pinboard Bookmarking API to pull one of my latest bookmarks:
Using Twitter to predict stock moves | Analysis &amp; Opinion | - http://blogs.reuters.com/felix-salmon/2010/12/23/using-twitter-to-predict-stock-moves/
I have these curated bookmarks, but I want the text content from these URLs so I can evaluate it further.
I could pull the full content of the HTML page at the bookmark URL, but that would give me the entire site header and other content.
I want just the blog post content.   Nothing else.
So using the Alchemy Text Extraction Web API I pull the text for the Pinboard bookmark:
This paper, which has now become a fully-fledged hedge fund, is certainly good at hitting buttons: not only does it include Twitter and stocks, but it even finds room to include an important role for Google n-grams!
The beating heart of the paper is this chart, which purports to show a connection between two data series. The blue line is the amount that the Dow rose or fell on any given day; the red line is the frequency with which people are saying I feel calm, or words to that effect, on Twitter.
 To my untrained eye, I have to admit that all I see here is two random lines layered on top of each other. But according to the paper, if you run this data through a Granger Causality Analysis and then a Self-Organizing Fuzzy Neural Network, you get all manner of enticing predictive power out the other end. In the chart, the shaded areas supposedly show the periods where Twitter successfully predicted where the stock market was going.
Conceptually, I suppose it makes a certain amount of sense that stocks would fall when people stop feeling calm (nervousness causes selling) and rise when they do feel calm, and therefore more comfortable betting on the future.
It also makes sense that if you're going to try to use Twitter to predict moves in the stock market, you want to concentrate on what it's good at, which is giving a real-time glimpse into the sentiment of millions of people. As Pascal-Emmanuel Gobry points out, the algorithm here deliberately strips out stock-related tweets.
I'm sure that the new hedge fund, called Derwent Capital Markets, will be shelling out the maximum $360,000 a year for access to 50% of Twitter's live stream. So someone's making money here. But I'm skeptical that Derwent is going to be very successful. After all, predictive power isn't enough to make money in the stock market: it's perfectly possible to make money 87.6% of the time but still lose money over the long run.
I also suspect that these kind of algorithms are going to have difficulty keeping up with Twitter as it evolves away from people broadcasting the minutiae of their lives, and towards more sophisticated conversations which are less susceptible to n-gram analysis. But the Derwent crew will certainly be doing some very sophisticated and interesting research on Twitter in the coming months and years. I hope that, eventually, they'll make some of their results public.
Good example of using the Pinboard Bookmarking API to pull bookmarks, then use the Alchemy Text Extraction Web API to get the content of each bookmark.
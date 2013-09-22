---
layout: post
title: "Mining of Massive Data Sets"
url: 'http://kinlane.com/2010/12/30/mining-of-massive-data-sets/'
image: 'http://kinlane-productions.s3.amazonaws.com/database/mining-data-sets.jpg'
---

<img src="http://kinlane-productions.s3.amazonaws.com/database/mining-data-sets.jpg" alt="" width="250" align="right" />Mining of Massive Data Sets is a book evolved from material developed over several years by Anand Raja- raman and Jeff Ullman for a one-quarter course at [Stanford][1]. The course titled Web Mining, was designed as an advanced graduate course, although it has become accessible and interesting to advanced undergraduates.

At the highest level of description, this book is about data mining. However, it focuses on data mining of very large amounts of [data][2], that is, data so large it does not fit in main memory.

The book takes an algorithmic point of view: data mining is about applying algorithms to data, rather than using data to train a machine-learning engine of some sort. The principal topics covered are:

  * Distributed file systems and map-reduce as a tool for creating parallel algorithms that succeed on very large amounts of data.
  * Similarity search, including the key techniques of and locality- sensitive hashing.
  * Data-stream processing and specialized algorithms for dealing with data that arrives so fast it must be processed immediately or lost.
  * The technology of search engines, including [Google][3]'s PageRank, link-spam detection, and the hubs-and-authorities approach.
  * Frequent-item set mining, including association rules, market-baskets, the A-Priori Algorithm and its improvements.
  * Algorithms for clustering very large, high-dimensional datasets.
  * Two key problems for Web applications: managing advertising and recommendation systems.
You can download the book [Mining of Massive Data Sets][4] from Standard.

   [1]: http://www.stanford.edu/
   [2]: ../category/data-20/
   [3]: http://www.kinlane.com/category/google/
   [4]: http://infolab.stanford.edu/~ullman/mmds/book.pdf

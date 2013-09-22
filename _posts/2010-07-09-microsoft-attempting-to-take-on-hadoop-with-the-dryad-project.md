---
layout: post
title: "Microsoft Attempting to Take on Hadoop with the Dryad Project"
url: 'http://kinlane.com/2010/07/09/microsoft-attempting-to-take-on-hadoop-with-the-dryad-project/'
image: 'http://hadoop.apache.org/zookeeper/images/hadoop-logo.jpg'
---

<img class="alignnone c1" title="Hadoop" src="http://hadoop.apache.org/zookeeper/images/hadoop-logo.jpg" alt="" width="300" height="71" align="right" />I'm learning more and more about distributed computing as I"m playing with larger and larger volumes of data. I understand a lot of the concepts behind the popular distributed computing platform [Hadoop][1], but have no actual experience deploying it. I'm diving into all the building blocks of [Hadoop][1] one by one as I have time:

  * [Hadoop Common][2] \- The common utilities that support the other Hadoop subprojects.
  * [Chukwa][3] -A data collection system for managing large distributed systems.
  * [HBase][4] \- A scalable, distributed database that supports structured data storage for large tables.
  * [HDFS][5] \- A distributed file system that provides high throughput access to application data.
  * [Hive][6] \- A data warehouse infrastructure that provides data summarization and ad hoc querying.
  * [MapReduce][7] \- A software framework for distributed processing of large data sets on compute clusters.
  * [Pig][8] \- A high-level data-flow language and execution framework for parallel computation.
  * [ZooKeeper][9] \- A high-performance coordination service for distributed applications.
Tonight, a post that really opened my eyes to some of the features and the approach Hadoop takes, was [A High Level Comparison of Hadoop and Dryad][10]. Not sure why, but the comparison of Hadoops approach using [Map Reduce][11] and Microsoft's approach using [Directed Acyclic Graph][12] has got me reading more. I think its because of my history with Windows Server, SQL Server and being a recovering Microsoft Kool-Aid drinker that this comparison is shedding light on Hadoop for me.

It appears appears that Microsoft is attempting to take on the [Hadoop][1] community with its [Dryad Project][13]. I'm way behind in understanding and applying [Hadoop][1], but Josh Patterson's comparison has pushed me into learning more. Thanks Josh.

   [1]: http://hadoop.apache.org/
   [2]: http://hadoop.apache.org/common/
   [3]: http://hadoop.apache.org/chukwa/
   [4]: HBase
   [5]: http://hadoop.apache.org/hdfs/
   [6]: http://hadoop.apache.org/hive/
   [7]: http://hadoop.apache.org/mapreduce/
   [8]: http://hadoop.apache.org/pig/
   [9]: http://hadoop.apache.org/zookeeper/
   [10]: http://jpatterson.floe.tv/index.php/2009/07/20/a-high-level-comparison-of-hadoop-and-dryad/
   [11]: http://en.wikipedia.org/wiki/MapReduce
   [12]: http://en.wikipedia.org/wiki/Directed_acyclic_graph
   [13]: http://research.microsoft.com/en-us/projects/Dryad/

---
layout: post
title: Microsoft Attempting to Take on Hadoop with the Dryad Project
url: http://kinlane.com/2010/07/09/microsoft-attempting-to-take-on-hadoop-with-the-dryad-project/
image: http://hadoop.apache.org/zookeeper/images/hadoop-logo.jpg
---
{% include JB/setup %}
I'm learning more and more about distributed computing as I"m playing with larger and larger volumes of data. I understand a lot of the concepts behind the popular distributed computing platform Hadoop, but have no actual experience deploying it. I'm diving into all the building blocks of Hadoop one by one as I have time:

	Hadoop Common - The common utilities that support the other Hadoop subprojects.
	Chukwa -A data collection system for managing large distributed systems.
	HBase - A scalable, distributed database that supports structured data storage for large tables.
	HDFS - A distributed file system that provides high throughput access to application data.
	Hive - A data warehouse infrastructure that provides data summarization and ad hoc querying.
	MapReduce - A software framework for distributed processing of large data sets on compute clusters.
	Pig - A high-level data-flow language and execution framework for parallel computation.
	ZooKeeper - A high-performance coordination service for distributed applications.

Tonight, a post that really opened my eyes to some of the features and the approach Hadoop takes, was A High Level Comparison of Hadoop and Dryad. Not sure why, but the comparison of Hadoops approach using Map Reduce and Microsoft's approach using Directed Acyclic Graph has got me reading more. I think its because of my history with Windows Server, SQL Server and being a recovering Microsoft Kool-Aid drinker that this comparison is shedding light on Hadoop for me.
It appears appears that Microsoft is attempting to take on the Hadoop community with its Dryad Project. I'm way behind in understanding and applying Hadoop, but Josh Patterson's comparison has pushed me into learning more. Thanks Josh.
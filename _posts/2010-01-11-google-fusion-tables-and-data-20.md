---
layout: post
title: Google Fusion Tables and Data 2.0
url: http://apievangelist.com/2010/01/11/1205/
source: http://apievangelist.com/2010/01/11/1205/
domain: apievangelist.com
image: 
---
{% include JB/setup %}I pulled this from the Google Research Blog. I was going to write my own, but they said it all. I just modified a little:
Database systems are notorious for being hard to use. It is even more difficult to integrate data from multiple sources and collaborate on large data sets with people outside your organization. Without an easy way to offer all the collaborators access to the same server, data sets get copied, emailed and ftp'd--resulting in multiple versions that get out of sync very quickly.
Google Fusion Tables is an experimental system for data management in the cloud. It draws on the expertise of folks within Google Research who have been studying collaboration, data integration, and user requirements from a variety of domains. Fusion Tables is not a traditional database system focusing on complicated SQL queries and transaction processing. Instead, the focus is on fusing data management and collaboration: merging multiple data sources, discussion of the data, querying, visualization, and Web publishing. We plan to iteratively add new features to the systems as we get feedback from users.
You can upload tabular data sets . Rright now, they are supporting up to 100 MB per data set, 250 MB of data per user and you can share them with your collaborators or with the world. You can choose to share all of your data with your collaborators, or keep parts of it hidden. You can even share different portions of your data with different collaborators.
When you edit the data in place, your collaborators always get the latest version. The attribution feature means your data will get credit for its contribution to any data set built with it. And yes, you can export your data back out of the cloud as CSV files.
You can filter and aggregate the data, and you can visualize it on Google Maps or with other visualizations from the Google Visualization API. You can then embed these visualizations in other properties on the Web (e.g., blogs and discussion groups) by simply pasting some HTML code.
The power of data is truly harnessed when you combine data from multiple sources. Fusion Tables enables you to fuse multiple sets of data when they are about the same entities. In database speak, we call this a join on a primary key but the data originates from multiple independent sources.
But Fusion Tables doesn't require you and your collaborators to stop there. What if you don't agree on all of the values? Or need to understand the assumptions behind the data better? Fusion Tables enables you to discuss data at different granularity levels -- you can discuss individual rows or columns or even individual cells. If a collaborator with edit permission changes data during the discussion, viewers will see the change as part of the discussion trail.
I don't know about you guys but I think Fusion Tables is a game changer. It will democratize the company database that us IT guys have made complex and hidden from others.
Many organizations actually run off series of departmental, program and other spreadsheets. Google Fusion Tables is a great way to bring this all on the web securely and increase company access to data. While putting the data in the hands of the people who truly own it.
URL: http://tables.googlelabs.com/public/tour/tour1.html

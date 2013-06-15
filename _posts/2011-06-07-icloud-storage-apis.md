---
layout: post
title: iCloud Storage APIs
url: http://kinlane.com/2011/06/07/icloud-storage-apis/
source: http://kinlane.com/2011/06/07/icloud-storage-apis/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/apple/iCloud-Steel.jpg
---
{% include JB/setup %}<p><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/apple/iCloud-Steel.jpg" alt="" width="150" align="right" /><a title="iCloud" href="http://www.apple.com/icloud/">iCloud</a> storage APIs allow IOS application developers to store documents and other data to a central location so userscan view or edit from any device without having to sync or transfer files.<p></p>
There are two ways that applications can take advantage of iCloud storage:
<ul class="mainlist">
	<li>Document Storage - Enabling storage and sharing of information in document form.</li>
	<li>Key-Value Data Storage - Enabling storage and sharing small amounts of data.</li>
</ul>
Most applications will use iCloud document storage to share documents, which is a feature that users think of when they think of cloud storage. Users care about whether photos, videos, and documents are accessible across devices while the key-value data store is not something a user would never see.<p></p>
Key-value storage will be used for small amounts of data such as storing application state, settings, and other important information that delivers a better user experience.  Although not as apparent to the end-user, key-value storage will be just as important as document storage.<p></p>
<img class="aligncenter" style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/apple/iCloud-Storage-APIs.png" alt="" width="550" align="center" /><p></p>
All iCloud storage is managed centrally by the iCloud service, which handles coordination of documents and key-value stores.  The iCloud service handles storage searches, change notifications, version control, conflicts, and security for applications that integrate with a user's iCloud storage account.<p></p>
Neither document storage or key-value storage in the cloud are anything new.  But when it is implemented as part of the IOS platform, it becomes much bigger.   Apple is solving everyday problems users face when using their smart phones, by storing data centrally in the cloud.<p></p>
<a title="iCloud APIs" href="http://blog.apievangelist.com/2011/06/08/icloud-storage-apis/">ICloud APIs</a> will enable developers to build rich applications on the IOS platform, and continue to grow IOS market share.</p>

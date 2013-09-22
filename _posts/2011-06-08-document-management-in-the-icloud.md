---
layout: post
title: "Document Management in the iCloud"
url: 'http://kinlane.com/2011/06/08/document-management-in-icloud/'
image: 'http://kinlane-productions.s3.amazonaws.com/apple/iCloud-Document-Storage.png'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/apple/iCloud-Document-Storage.png" alt="" width="270" align="right" />Apple's new [iCloud platform][1] provides a centralized cloud storage solution for managing documents from any computer and iOS device.

iCloud document storage is not just cloud storage. It provides a complete document management solution that keeps files synced between a user's mobile and desktop devices, with a copy always available in the cloud.

When any documents is created on a device using iCloud document storage it first gets stored in the application's local sandbox and moved to a user's iCloud account later. On its way to the iCloud, it is first moved out of the application's local sandbox and into a local system-managed directory where it can be monitored by the iCloud service. After that transfer, the file is transferred to iCloud and to the user's other devices when network conditions are optimal.

The iCloud storage service requires files to be stored locally to prevent large numbers of conflicting changes from occurring at the same time. The iCloud storage service uses file coordinators to mediate changes between applications and the service that facilitates the transfer of the document to and from iCloud. The file coordinator acts like a locking mechanism for documents, preventing applications and the storage service from modifying the document simultaneously.

Applications that store documents to iCloud specify one or more containers and sub-directories in which to store documents in a user's iCloud account. Applications have control over naming and creating their own storage containers, but have to request access for a user's iCloud Storage, allowing users to manage exactly what gets stored in the cloud.

When storing documents using iCloud, applications don't need to store the full URL to document. The iCloud storage service handles assigning a URL to the most recent document, with appropriate container and sub-directories as it transitions between devices and the iCloud. When an application queries a document it will always return the correct URL, location and version.

In addition to file sync and storage users can also opt to have their applications and application settings backed up directly to their iCloud account, making it easier to restore applications to their most recent state on any new or existing iOS device.

The iCloud Storage service handles end to end syncing and backing up for all user's documents--handling local storage, version control, conflict resolution, transferring to the cloud, and between all their devices.

Apple offers access to iCloud Storage services to iOS application developers via [iCloud Storage APIs][2], so the same document management features are available across any application installed on Mac Desktop, Laptops, IPhone, IPod and IPad devices.

Apple's intent is to not just provide cloud storage, they want to provide a seamless experience for users across all applications and devices so they don't have to think about where their music, video, images, and other documents are. It just happens.

######  Related articles

  * [Apple iCloud API][3] (apievangelist.com)
  * [iCloud Storage APIs][4] (kinlane.com)
  * [Documents in the Cloud with Apple iCloud][5] (kinlane.com)

   [1]: http://www.apple.com/icloud/ (iCloud Platform)
   [2]: http://blog.apievangelist.com/2011/06/08/icloud-storage-apis/ (iCloud Storage APIs)
   [3]: http://blog.apievangelist.com/2011/06/06/apple-icloud-api/
   [4]: http://www.kinlane.com/2011/06/icloud-storage-apis/
   [5]: http://www.kinlane.com/2011/06/documents-in-the-cloud-with-apple-icloud/

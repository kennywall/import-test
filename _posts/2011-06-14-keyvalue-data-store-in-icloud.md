---
layout: post
title: "Key-Value Data Store in iCloud"
url: 'http://kinlane.com/2011/06/14/key-value-data-store-in-icloud/'
image: 'http://kinlane-productions.s3.amazonaws.com/apple/icloud-stainless-3-devices-key-value.png'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/apple/icloud-stainless-3-devices-key-value.png" alt="" width="275" align="right" />Apple's new [iCloud platform][1] includes a new [key-value data][2] store, along side its [document storage][3].

An application can use the key-value data store to put small amounts of data in the cloud, and share with other instances of the same application running on other computers and IOS devices.

The key-value data store is meant to save simple data types (numbers, strings, dates, and arrays) persistently and retrieve later.

The amount of available space in a single key-value store is limited to 64 KB and the data for a single key cannot exceed 4 KB. This size allows the storage of small details from an application, but should not be used to store user documents or other large data objects, this should be done with [iCloud document storage][4].

Before an application can have access to a users key-value data stores it must request specific entitlements, in order to use iCloud storage. This ensures a user has control over what gets stored in their iCloud account.

The container identifier string must be of the form

   [1]: http://www.apple.com/icloud/ (iCloud platform)
   [2]: http://en.wikipedia.org/wiki/Associative_array (Associative array)
   [3]: http://www.kinlane.com/2011/06/document-management-in-icloud/ (document storage)
   [4]: http://blog.apievangelist.com/2011/06/08/icloud-storage-apis/ (iCloud document storage)

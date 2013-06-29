---
layout: post
title: Key Value Data Store in iCloud
url: http://kinlane.com/2011/06/14/key-value-data-store-in-icloud/
image: http://kinlane-productions.s3.amazonaws.com/apple/icloud-stainless-3-devices-key-value.png
---
{% include JB/setup %}
Apple's new iCloud platform includes a new key-value data store, along side its document storage.
An application can use the key-value data store to put small amounts of data in the cloud, and share with other instances of the same application running on other computers and IOS devices.
The key-value data store is meant to save simple data types (numbers, strings, dates, and arrays) persistently and retrieve later.
The amount of available space in a single key-value store is limited to 64 KB and the data for a single key cannot exceed 4 KB. This size allows the storage of small details from an application, but should not be used to store user documents or other large data objects, this should be done with iCloud document storage.
Before an application can have access to a users key-value data stores it must request specific entitlements, in order to use iCloud storage.  This ensures a user has control over what gets stored in their iCloud account.
The container identifier string must be of the form &lt;TEAM_ID&gt;.&lt;CUSTOM_STRING&gt;, where &lt;TEAM_ID&gt; is the unique ten-character identifier associated with an application developer account. The contents of &lt;CUSTOM_STRING&gt; can be anything that makes sense to your application. You can even use the same container identifier string for multiple applications if you want them to share the same storage space.
The value of the container identifiers key is an array of strings. The first string in this array must be the main container identifier to associate with the application. Companies that develop multiple applications, can include additional container identifiers.
Some examples of key-value usage might be, storing the current page or section of an application, so when the user returns to the applicaiton on same device or other devices, it opens to that same page and section.
iCloud key-value storage is meant to empower developers with a centralize storage to use between devices, that enhances the user experience on Mac and iOS devices.
Related articles

	iCloud Storage APIs (apievangelist.com)
	Apple iCloud API (apievangelist.com)
	Document Management in iCloud (kinlane.com)


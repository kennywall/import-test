---
layout: post
title: Google Storage for Developers Interoperability
url: http://apievangelist.com/2010/09/01/google-storage-for-developers-interoperability/
source: http://apievangelist.com/2010/09/01/google-storage-for-developers-interoperability/
domain: apievangelist.com
image: http://code.google.com/images/code_labs_logo.gif
---
{% include JB/setup %}<p>I finally got my Google Storage for Developers email invite the other day. They promised attendees of Google I/O would get them quicker, it took 3 months.
I clicked on the link in my email and requested my keys and logged into the Google Storage Manager.
It has a pretty basic interface for managing your buckets and objects. Just like Amazon S3.
Then I wanted to test out the interoperability of it. Google claims:
Google Storage is interoperable with a large number of cloud storage  tools and libraries that work with services such as Amazon Simple  Storage Service.
So I downloaded a common Amazon S3 PHP Class and changed the request endpoints, request headers, signature identifiers, ACLs, query string parameters and used my Google developer keys.
And it work. It listed my buckets I had created through the Google Storage Manager. I am playing with more to see how I can store files and content at both Amazon S3 and Google Developer Storage.
Now to figure out what I will use Google Storage for vs. Amazon S3.
</p>
<center><p><a href="http://apievangelist.com/2010/09/01/google-storage-for-developers-interoperability/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>

---
layout: post
title: "Proofing a Scribd PDF Using Mimeo Connect"
url: 'http://kinlane.com/2011/01/11/proofing-scribd-pdf-using-mimeo-connect/'
image: ''
---

Now the PDF we pulled from Scribd is proofed. With the Product ID returned from the Mimeo Proof Service we can get the details of the proof.

We need to make a second call to the Proof Service and Get the Proof.

`$root_url = "connect.sandbox.mimeo.com/2010/09/"; $user_name = "[user name]"; $password = "[user password]"; $rest = new MimeoRESTclient($root_url,$user_name,$password);$documentId = "702e6c5b-35d8-4ffb-8d3c-cf779d9a13eb"; $url = "ProofService/Proof/" . $Product_ID;`

`$rest-`
---
layout: post
title: TeleHah Distributed JSON Peering Protocol
url: http://kinlane.com/2010/06/15/teleha%e2%9a%a1h-distributed-json-peering-protocol/
image: http://jeremie.com/i/810c8079d4a77e514296b3a58710c903.png
---
{% include JB/setup %}

It works by sending and receiving very simple small bits of JSON  via UDP using an easy routing system based on Kademlia, a proven and  popular Distributed  Hash Table.  Everything within TeleHash is routed based on a  generic SHA hash, usually of something specific to an application or something  common like a URL.
While it is still young, the protocol and early implementations  are evolving quickly and can already be used. Everyone is welcome to  start experimenting and get involved in any form.
URL:  http://telehash.org/
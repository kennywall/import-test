---
layout: post
title: "TeleHa?h - Distributed JSON Peering Protocol"
url: 'http://kinlane.com/2010/06/15/teleha%e2%9a%a1h-distributed-json-peering-protocol/'
image: 'http://jeremie.com/i/810c8079d4a77e514296b3a58710c903.png'
---

<img class="alignnone c1" title="TeleHash" src="http://jeremie.com/i/810c8079d4a77e514296b3a58710c903.png" alt="" width="284" height="180" align="right" />TeleHash is a new wire protocol for exchanging [JSON][1] in a real-time and fully decentralized manner, enabling applications to connect directly and participate as servers on the edge of the network. It is designed to efficiently route and distribute small bits of data in order for applications to discover each other directly or in relation to events around piece of shared content. The core benefits of TeleHash over other similar platforms and protocols is that it is both generic (not tied to any specific application or content structures) and is radically decentralized with no servers or points of central control.

It works by sending and receiving very simple small bits of JSON via [UDP][2] using an easy routing system based on [Kademlia][3], a proven and popular [Distributed Hash Table][4]. Everything within TeleHash is routed based on a generic [SHA][5] hash, usually of something specific to an application or something common like a URL.

While it is still young, the protocol and early implementations are evolving quickly and can already be used. Everyone is welcome to start experimenting and get involved in any form.

**URL:** 

   [1]: http://www.json.org/
   [2]: http://en.wikipedia.org/wiki/User_Datagram_Protocol
   [3]: http://en.wikipedia.org/wiki/Kademlia
   [4]: http://en.wikipedia.org/wiki/Distributed_hash_table
   [5]: http://en.wikipedia.org/wiki/Secure_Hash_Algorithm

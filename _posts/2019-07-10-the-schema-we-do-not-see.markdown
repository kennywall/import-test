---
published: true
layout: post
title: The Schema We Do Not See
date: 2019-07-10T09:00:00.000Z
tags:
  - Kin Lane
image: https://s3.amazonaws.com/kinlane-productions/algorotoscope-master/two-sattelite-dishes-leaflets-of-the-russian-revolution.jpg
---
I am doing a lot of work with schema objects lately. In some cases I am the one who defines, and in other cases I am working to better understand the difference between the schema that gets exposed through APIs, to web and mobile applications, and what actually exists under the hood of the applications we use each day. Schema are the name and properties of the digital bits we generate within these applications each day, from a photo post to Instagram, to the location of our mobile phone with each step we take, schema are the templates that define our on, and increasingly offline behavior each day. I’m being paid to understand schema at this level, but I also do a lot of extra, non-paid work trying to understand the seen, and the unseen properties of the schema we generate across the platforms we operate each day.

There is so much going on beneath the surface of the applications we depend on, and I’m determined to better understand as well as shine a light on what is going on within these layers. Let’s take a basic Tweet. What do you see when I Tweet?

<p align="center"><img src="https://kinlane-productions.s3.amazonaws.com/leftover-tweet.png" width="100%"></p>

That is just the tip of the API iceberg. When you make an API call for the same Tweet, you get a look at the “full” schema for this tweet:
```
statuses:
- created_at: Fri Jul 05 21:18:55 +0000 2019
  id: 1147253546410098700
  id_str: '1147253546410098688'
  text: 'Leftover mashup from the last two days: Kimchi Meatloaf, Fried chicken tenders,
    macaroni salad, and biscuit — all h… https://t.co/o2ZE2DJf8F'
  truncated: true
  entities:
    hashtags: []
    symbols: []
    user_mentions: []
    urls:
    - url: https://t.co/o2ZE2DJf8F
      expanded_url: https://twitter.com/i/web/status/1147253546410098688
      display_url: twitter.com/i/web/status/1…
      indices:
      - 117
      - 140
  metadata:
    iso_language_code: en
    result_type: recent
  source: <a href="https://mobile.twitter.com" rel="nofollow">Twitter Web App</a>
  in_reply_to_status_id:
  in_reply_to_status_id_str:
  in_reply_to_user_id:
  in_reply_to_user_id_str:
  in_reply_to_screen_name:
  user:
    id: 5954192
    id_str: '5954192'
    name: Kin Lane
    screen_name: kinlane
    location: Seattle, WA
    description: I am a writer. I like telling stories. I like playing with images.
      I also do things with the Internet as the API architect at F5 Networks.
    url: https://t.co/8qR9jIDiSG
    entities:
      url:
        urls:
        - url: https://t.co/8qR9jIDiSG
          expanded_url: http://kinlane.com
          display_url: kinlane.com
          indices:
          - 0
          - 23
      description:
        urls: []
    protected: false
    followers_count: 14354
    friends_count: 8721
    listed_count: 677
    created_at: Fri May 11 08:17:59 +0000 2007
    favourites_count: 11289
    utc_offset:
    time_zone:
    geo_enabled: true
    verified: false
    statuses_count: 4190
    lang:
    contributors_enabled: false
    is_translator: false
    is_translation_enabled: false
    profile_background_color: 1A1B1F
    profile_background_image_url: http://abs.twimg.com/images/themes/theme9/bg.gif
    profile_background_image_url_https: https://abs.twimg.com/images/themes/theme9/bg.gif
    profile_background_tile: false
    profile_image_url: http://pbs.twimg.com/profile_images/1139394614643658754/X-PvqUTV_normal.png
    profile_image_url_https: https://pbs.twimg.com/profile_images/1139394614643658754/X-PvqUTV_normal.png
    profile_banner_url: https://pbs.twimg.com/profile_banners/5954192/1560487874
    profile_link_color: ABB8C2
    profile_sidebar_border_color: FFFFFF
    profile_sidebar_fill_color: '252429'
    profile_text_color: '666666'
    profile_use_background_image: true
    has_extended_profile: true
    default_profile: false
    default_profile_image: false
    following:
    follow_request_sent:
    notifications:
    translator_type: none
  geo:
  coordinates:
  place:
  contributors:
  is_quote_status: false
  retweet_count: 0
  favorite_count: 5
  favorited: false
  retweeted: false
  possibly_sensitive: false
  lang: en
search_metadata:
  completed_in: 0.048
  max_id: 1147439612383678500
  max_id_str: '1147439612383678465'
  next_results: "?max_id=1144723262863269887&q=kinlane&count=100&include_entities=1"
  query: kinlane
  refresh_url: "?since_id=1147439612383678465&q=kinlane&include_entities=1"
  count: 100
  since_id: 0
  since_id_str: '0'
```

I do not have my geographic settings turned on, so I’m not recording those data points. However, there is a still a lot of schema behind the scenes of this single tweet that contains relevant data points about my world, providing context to the tweet, but also widening the behavioral snapshot of my personal world. Anyone can pull this data using the Twitter API. All you need is an API key, and the id of a user, and you can obtain this “full” view of what schema exists behind each and every tweet. There is a lot of data the average user doesn’t see, or is burdened with. This layer of the web is primarily the domain of developers, but that is just one of several dimensions—-there is also the provider view, or in this case, what Twitter sees.

The schema I posted is just one portion of the schema you see behind each Tweet. Twitter possess even more data than this, providing access to logging, cookie, and other dimensions that take things much further than what is listed here. This is what we see going over the API pipes between a desktop, web, or mobile application and the Twitter mothership, but there is a whole other set of data behind Twitter’s API servers. I consider there to be four layers of schema for defining and providing access to our regular social behavioral patterns:

- **User** - What the user sees through the desktop, web, or mobile interface.
- **Developer** - What the application developer sees through the API.
- **Provider** - What the API provider has access to that isn’t exposed to applications.
- **Partner** - What the API provider partners have access to behind the scenes.

These four layers of schema are made available to four very different actors. Depending on who you are, you have a different view of the schema. There are also two other key variables that come into play when discussing who can see different parts of the schema, and who is entitled to even know about, let alone have any decision making capability around the data stored within the platform schema.

- **Device** - What data objects using specific schema are created, and stored on a device, in a user’s home, car, business, or in their pocket.  
- **Server** - What data objects using specific schema are created, and stored on a server within a companies own datacenter.

The picture I’m painting here isn’t about data ownership or specifically data privacy. I’d say it is more about data awareness, and data voice—having a say in what happens to your data. Most platform, API, and application providers feel free to generate, store, process, and own data about you, generated on your devices, within your home, just because it was facilitated with their software. I am trying to connect all the dots when it comes to the data we generate each day, but work to also shine a light on the data we do not know about. I know there are a number of folks who feel like this data is free for the taking, simply because users do not know it exists. It’s not private data, if you don’t know that you have it.

It is this technological sleight of hand that bothers me. It is a form of exploitation via complexity and consuion. If you make something complicated enough on the web, and hide it right beneath the surface, where few people will see--you can not only get away with doing things inside someones personal space, but you can surveil, track, and generate data which you can also sell or use as a raw material in the development of new digital products. It is a particularly invasive form of intrusion that is only being sanctioned because very few people can even see it. The layers of the schema are obfuscated differently, depending on where you are at in the overall supply chain.

I have separate but overlapping concerns when it comes to each of layers of schema in place across major tech providers. I have concerns about what is disclosed to users, as well as what is openly made available to 3rd party developers. But, I have the most concern about the portions of the schema that never see the light of day. The portions that us end-users have no idea exists, even though it is all data about us. The bits of our digital self that tech companies view as commodities, and actively use in products, and sometimes make accessible to partners, but refuse to ever tell us about, let alone give us a voice over what gets collected, and who has access to it. This is the schema that keeps me up at night. I feel like 95% of it will be harmless, and act more as an annoyance, than anything particularly troubling. However, it is the 5% of the schema that I can’t see, that I can’t correct, or that I do not have any voice over that could end up impacting my credit, my career, and have real world consequences in my physical life.

---
title: Admin Configuration
layout: single
permalink: /admin/
classes: wide

sidebar:
  nav: "admin"

gallery:
  - url: /jamesFeed/player.html
    image_path: /jamesFeed/images/live.jpg
    alt: "James Feed for Mixing"
    title: "CCA West Stream"

feature_row:
  - image_path: /jamesFeed/images/live.jpg
    alt: "James Custom Feed"
    title: "James Custom livestreams"
    excerpt: 'View live streams mixed with other sources.'
    url: "/jamesFeed/player.html"
    btn_label: "Custom Feed"
    btn_class: "btn--info"
    actions:
      - label: "Watch"
        url: "/jamesFeed/player.html"
        btn_class: "btn--info"
      - label: "configure stream"
        url: "/jamesFeed/"
        btn_class: "btn--danger"



---

Streams can be managed below through the links to the [Restreamer server](https://github.com/datarhei/restreamer). New streams cannot be created here, for that you must contact the [admin](mailto:james@site-walk.org) 

> If you see the **(Error: Your stream wasn't accessible. .... Operation not permitted)** the system is functioning. Send some stream there and it will work

You must ensure that the stream is started and is listening in the stream config link.

See the [setup guide](/admin/setup) for more instruction. 

## Custom Feed 

Use this feed for custom mixed events using some software like [OBS](https://obsproject.com/) to add content.


{% include feature_row id="feature_row" type="left" %}

## Setup


Each stream uses a seprate port to communicate with the video signal stream. Use the configuration details from below to connect the camera system to the server to stream.

---

{% include_relative .secretconfig %}
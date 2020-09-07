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


iframe:
  - url: /ccawest-main/player.html
    image_path: /ccawest-main/images/live.jpg
    alt: "CCA West Main"
    title: "CCA West Stream"
  - url: /ccawest-cx/player.html
    image_path: /ccawest-cx/images/live.jpg
    alt: "CCA West CX"
    title: "CCA West Stream"
  - url: /ccawest-cell/player.html
    image_path: /ccawest-cell/images/live.jpg
    alt: "CCA West Issue"
    title: "CCA West Stream"
  - url: /ccbwest-main/player.html
    image_path: /ccbwest-main/images/live.jpg
    alt: "CCB West Main"
    title: "CCB West Stream"
  - url: /ccbwest-cx/player.html
    image_path: /ccbwest-cx/images/live.jpg
    alt: "CCB West CX"
    title: "CCB West Stream"
  - url: /ccbwest-cell/player.html
    image_path: /ccbwest-cell/images/live.jpg
    alt: "CCB West Issue"
    title: "CCB West Stream"
  - url: /ccbeast-main/player.html
    image_path: /ccbeast-main/images/live.jpg
    alt: "CCB East Main"
    title: "CCB East Stream"
  - url: /ccbeast-cx/player.html
    image_path: /ccbeast-cx/images/live.jpg
    alt: "CCB East CX"
    title: "CCB East Stream"
  - url: /ccbeast-cell/player.html
    image_path: /ccbeast-cell/images/live.jpg
    alt: "CCB East Issue"
    title: "CCB East Stream"
  - url: /ccceast-main/player.html
    image_path: /cccceast-main/images/live.jpg
    alt: "CCC East Main"
    title: "CCC East Stream"
  - url: /ccceast-cx/player.html
    image_path: /ccceast-cx/images/live.jpg
    alt: "CCC East CX"
    title: "CCC East Stream"
  - url: /ccceast-cell/player.html
    image_path: /ccceast-cell/images/live.jpg
    alt: "CCC East Issue"
    title: "CCC East Stream"

---

Streams can be managed below through the links to the [Restreamer server](https://github.com/datarhei/restreamer). New streams cannot be created here, for that you must contact the [admin](mailto:james@site-walk.org) 

> You must ensure that the stream is started and is listening. <br>If you see the **(Error: Your stream wasn't accessible. .... Operation not permitted)** the system is functioning. Send some stream there and it will work


{% include iframe caption="Images shown here are the last captured image from the previous stream." %}

---

## Custom Feed 

Use this feed for custom mixed events using some software like [OBS](https://obsproject.com/) to add content.


{% include feature_row id="feature_row" type="left" %}

## Setup


Each stream uses a seprate port to communicate with the video signal stream. Use the configuration details from below to connect the camera system to the server to stream.

---

{% include_relative .secretconfig %}
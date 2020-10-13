---
title: Admin Configuration
layout: single
permalink: /admin/

toc: true
toc_label: "Admin TOC"
toc_icon: "cog"
toc_sticky: true

sidebar:
  nav: "admin"




restreamer:
  - url: /assets/img/RestreamerStopped.png
    image_path: /assets/img/RestreamerStopped-th.png
    alt: "Stopped instance"
    title: "Stopped instance, Press that green START!"
  - url: /assets/img/RestreamerInterface.png
    image_path: /assets/img/RestreamerInterface-th.png
    alt: "Running instance"
    title: "Running instance"
  - url: /assets/img/RestreamerRunning.png
    image_path: /assets/img/RestreamerRunning-th.png
    alt: "Running stream with live video available"
    title: "Running stream with live video available"
  - url: /assets/img/RestreamerOptional.png
    image_path: /assets/img/RestreamerOptional-th.png
    alt: "Optional h.264 External Stream"
    title: "Optional External h.264 Stream (Youtube shown)"

---

Instructions for the setup and use of the video server. 

## Streaming Setup

Manage streams through the links to the [Restreamer server](https://github.com/datarhei/restreamer) instances running on this server shown in the table or in the **Stream Config** links on the left or in the table below.


### Stream Config Links

{% include_relative .secretconfig %}

Each stream is a Docker container running the Restreamer server. The stream must be started in order to run. This is accomplished through the Restreamer admin interface. 

*(Please reach out to the administrator for a password to configure these streams.)*

{% include gallery id="restreamer" layout="half" caption="" %}



### Configuration 



New streams cannot be created here, for that you must contact the [admin](mailto:james@site-walk.org) 

> If you see the **(Error: Your stream wasn't accessible. .... Operation not permitted)** the system is functioning. Send some stream there and it will work

You must ensure that the stream is started and is listening in the stream config link.

See the [setup guide](/admin/setup) for more instruction. 



## Setup


Each stream uses a separate port to communicate with the video signal stream. Use the configuration details from below to connect the camera system to the server to stream.

---


{% include_relative .secretconfig.player %}


## Custom Feed 

Use this feed for custom mixed events using some software like [OBS](https://obsproject.com/) to add content.



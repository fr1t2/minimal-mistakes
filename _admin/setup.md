---
layout: single
classes:
  - dark-theme

author_profile: false
entries_layout: grid
permalink: /admin/setup/
title: "Site-Walk Hardware Setup"
toc: true
toc_label: "Admin TOC"
toc_icon: "cog"
toc_sticky: true

sidebar:
  nav: "admin"

header:
  overlay_color: "#000"
  overlay_filter: "0.75"
  overlay_image: /assets/img/camSetupHeader.png
  caption: "Photo credit: [**CEP**](#)"
excerpt: "How it all fits together!"

gallery:
  - url: /assets/img/gopro-h8b.png
    image_path: /assets/img/gopro-h8b-th.png
    alt: "Camera Assembly"
    title: "Assembly details"

gopro-gallery:
  - url: /assets/img/goproFront-wh.png
    image_path: /assets/img/goproFront-th.png
    alt: "Camera Front"
    title: "GoPro Hero 8 Front"
  - url: /assets/img/goproSide-wh.png
    image_path: /assets/img/goproSide-th.png
    alt: "Camera Side"
    title: "GoPro Hero 8 Side"
  - url: /assets/img/goproRear-wh.png
    image_path: /assets/img/goproRear-th.png
    alt: "Camera Back"
    title: "GoPro Hero 8 Back"
  - url: /assets/img/goproSide2-wh.png
    image_path: /assets/img/goproSide2-th.png
    alt: "Camera Front"
    title: "GoPro Hero 8 Side 2"

teradek-gallery:
  - url: /assets/img/vidiugo-components-wh.png
    image_path: /assets/img/vidiugo-components-th.png
    alt: "Camera Front"
    title: "GoPro Hero 8 Front"

teradek-gallery2:
  - url: /assets/img/vidiuDashboard.png
    image_path: /assets/img/vidiuDashboard-th.png
    alt: "Camera Front"
    title: "GoPro Hero 8 Front"

teradek-gallery3:
  - url: /assets/img/vidiu-bcastSettings-hl-ins.png
    image_path: /assets/img/vidiu-bcastSettings-th.png
    alt: "Camera Front"
    title: "GoPro Hero 8 Front"
---

## Setup Instructions 

This kit has been assembled to accomplish the streaming needs from remote sites without reliable Wifi connections. There are quite a few parts that must work together for this service to work.

This guide walks through the connection and setup to get a stream started.

> If you have any questions about how things work, Please see the device instructions in the sidebar on the left.


## Technology

Basic Components of the system:

![image-right](/assets/img/OnAirlogo320.png){: .align-right .full}

* GoPro Hero 8 Camera 
* Stabilization Gimbal
* Teradek streaming encoder
* Omnicharge Ultimate battery
* Extension poles for gimbal
* Backpack to hold it all together

> For the full list see the documents in the camera bag.

### Physical Assembly

Connecting everything.



### Cabling and Connections

How to plug it together

## Hardware

### Go Pro Hero 8
![image-right](/assets/img/gopro-h8b-th.png){: .align-right}

Simple to use action camera for both recording video locally as well as streaming to the site. 

The camera has a micro SD card installed that will allow up to 2.5 hours of video to be recorded. While streaming the camera does not need to be recording to stream. 

{% include gallery id="gopro-gallery" layout="half" caption="" %}

> While connected to the Teradek Encoder the rear touch screen is disabled and the front screen will show an external screen icon. 

#### Clearing the Display

There are a few steps to clearing the on screen display from the video feed and must be done every startup.


1. Connect the camera to power and video
2. Power on the Encoder
3. Power on the camera
4. Press the **Mode Button** 2 times
5. Press the **Shutter Button** 1 time
6. Press the **Mode Button** 4 times
7. Press the **Shutter Button** 1 time

<ins>The screen is now clear and ready to stream!</ins>

#### Recording while Streaming

Once the screen is clear and the encoder is connected you can *optionally* record the video directly on the GoPro. This video then can be uploaded for later viewing. **See the Uploading section FIXME**

1. With the camera powered on Press the Shutter button to begin recording. 
2. Press again to stop. 

> Audio is recorded with the video directly on the camera. Watch what you say while recording!

#### Downloading Videos

To remove the recordings from the camera and save them to a computer or HDD:

1. Remove the SD Card from the camera
2. Insert into a card reader
3. Transfer files
4. Reinstall SD card into camera


### Teradek Vidiu Go

![image-right](/assets/img/vidiugo-th.png){: .align-left}

The *Teradek Vidiu Pro* is the component responsible for getting the video online. This device takes the video signal from the camera and encodes it into web traffic and sends it to our streaming server. 

There is a lot going on here, however once setup it is as simple as pressing the stream button.

{% include gallery id="teradek-gallery" layout="half" caption="Vidiu Go Encoder details" %}


#### Basic Streaming

1. Power on the encoder
2. Wait for all of the network connections to establish. You must be connected for the system to function
3. Browse to broadcast settings in the menu and select the correct stream destination
4. With video connected press the red streaming button and confirm the selection
5. Stream is live! Log into the correct page and view the feed

#### Web Interface

The Teradek Vidiu Go will serve up a configuration page if you are connected directly to the unit in AP mode, or if you are on the same internal LAN either wired or wireless.

Browse to the IP address shown on the unit when you press the down arrow.

{% include gallery id="teradek-gallery2" layout="half" caption="Vidiu Go Encoder details" %}

#### Broadcast Settings

{% include gallery id="teradek-gallery3" layout="half" caption="" %}

Select the stream to send video to in the `Settings tab --> broadcast --> manage` and select one of the pre-stored stream destinations.


> You will need to use the corresponding link to view the stream.


#### Network Settings

The Encoder can utilize multiple network connections to send the stream. Typically either WIFI *(prefered)* or Cellular will be used to transmit the video feed.

##### Wifi

Enter the network menu and configure the wifi to use a nearby network.

##### Cellular

NEED TO CONFIGURE THIS STILL!



### Gimbal 

## Software

### Streaming

#### Local Services

#### External Services 



### Uploading video









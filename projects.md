---
layout: page
title: Projects
permalink: /projects/
order: 2
---

## Raspberry Pi timelapse camera

<img alt="timelapse photo" src="{{ "/assets/timelapse.jpg" | absolute_url }}">

For the 2017-2018 refurbishment project at Collingwood College (in which I was heavily involved - see the CV page for more details), I made a timelapse camera to capture the progress of the project from the roof of an adjacent building. This was achieved using a Raspberry Pi (and Raspberry Pi camera) inside a gutted outdoor floodlight, powered using a PoE (Power over Ethernet) adapter.

The bash script is available on [GitHub](https://github.com/browningjp/timelapse).

#### Technologies used

* Raspberry Pi
* Linux
* Bash
* ffmpeg

## WordPress plugins for Oscar Box Office

For Durham Student Theatre, I wrote two WordPress plugins to integrate their SaaS box office system (Oscar, from Savoy Systems) into their websites. The [first](https://github.com/browningjp/Oscar_WP_Widget) is a simple widget to display upcoming shows in the sidebar. The [second](https://github.com/browningjp/oscar_listings_shortcodes) plugin creates listing pages that filter shows based on which site they should be displayed on. For instance, some shows are student shows, so should appear on the [Durham Student Theatre website](https://www.durhamstudenttheatre.org). Some shows are in the Assembly Rooms Theatre, so should appear on the [Assembly Rooms website](https://www.theassemblyroomstheatre.org). Many shows, of course, are student shows in the Assembly Rooms, so they appear on both sites.

#### Technologies used

* PHP
* WordPress
* APIs (XML)

## Traffic Measurement with Arduino

In this project we created a traffic sensor using an Arduino UNO and an ultrasonic sensor, contained in an ice cream tub. The sensor was placed at the side of the road to detect when there is a car passing, and could even distinguish between two lanes of traffic. Data could be collected either via USB cable for live monitoring, or logged to an SD card for later retrieval allowing the device to be left unattended.

<img alt="traffic measurement" src="{{ "/assets/traffic.jpg" | absolute_url }}">

## Steganography in Live Video

For my final year undergraduate project, I investigated the feasibility of using live video as a cover object for steganography, i.e. hiding secret messages into live streaming video. I implemented a prototype application demonstrating embedding text-based messages into a live video stream using the LSB (least-significant bit) technique, and a second application to recover the hidden messages from the video. I evaluated the effectiveness of several techniques to preserve the integrity of the messages when the stream was subjected to lossy video compression.

<img alt="Steganography diagram" src="{{ "/assets/steg.png" | absolute_url }}">

Click [here]({{ "/assets/SteganographyInLiveVideo.pdf" | absolute_url }}) to download the final paper.
Click [here]({{ "/assets/SteganographyPoster.pdf" | absolute_url }}) to download the project poster.

#### Technologies used

* Python
* OpenCV
* NumPy

## Parcel Notification System

I developed a web application for reception staff to quickly and easily notify students that a parcel had arrived for them. The further development of this project then formed the basis of my software development internship in the university.

#### Technologies used

* PHP
* Laravel
* HTML
* CSS
* JavaScript
* jQuery
* MySQL



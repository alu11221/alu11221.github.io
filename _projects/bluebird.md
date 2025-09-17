---
title: "IR-Imaging UAS"
excerpt: "Custom autonomous thermal imaging drone for wildfire research."
layout: single
collection: projects
permalink: /projects/bluebird/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/bluebird/bluebird_iso_background.JPEG
  teaser: /assets/images/bluebird/bluebird_iso_background.JPEG
author_profile: true
toc: true
toc_sticky: true
toc_label: "Jump to section"
toc_icon: "plane-departure"
classes: custom-font-size
order: 3

gallery:
  - url: /assets/images/bluebird/eagle_background.JPEG
    image_path: /assets/images/bluebird/eagle_background.JPEG
  - url: /assets/images/bluebird/bluebird_iso_background.JPEG
    image_path: /assets/images/bluebird/bluebird_iso_background.JPEG

gallery2:
  - url: /assets/images/bluebird/bluebird_pdb.JPEG
    image_path: /assets/images/bluebird/bluebird_pdb.JPEG
  - url: /assets/images/bluebird/bluebird_escs.JPEG
    image_path: /assets/images/bluebird/bluebird_escs.JPEG
---

## Intro
The Laboratory for Autonomy in Data-Driven and Complex Systems (LADDCS) at The Ohio State University aims to use drones to help prevent and mitigate wildfires. When I first joined LADDCS, I was surprised to see such a forward-thinking lab using such antiquated drone equipment. Their in-house, low-cost drone platform dubbed the *Eagle* quickly proved to be unreliable and cumbersome to maintain. After experiencing multiple crashes in flight tests which required full rebuilds of the *Eagle*, I proposed that we invest in a modernized low-cost platform. Within a month, we began flight testing our new drone, the *BlueBird*.

{% include gallery caption="Old platform (*Eagle*) vs. new platform (*BlueBird*)." %}

## My Role
As the primary technical owner of all drone hardware during my time at LADDCS (Jan 2022 - May 2023), I was responsible for maintaining and testing all in-house drone platforms, as well as creating the *BlueBird*.

## Specifications
Basic specifications are listed below. See this [Info Sheet](https://docs.google.com/document/d/1uYRVa4Ni_aAR4jvPIlAYXMj6czKm5VwpNRkhNgGF88Q/edit?usp=sharing) for more details on the *BlueBird* platform.

| Specifications  |                                                                           |
|-----------------|---------------------------------------------------------------------------|
| Platform        | HolyBro X500 V2 Quadcopter                                                |
| Size            | 500mm (diagonal, motor-to-motor)                                          |
| Max Flight Time | 23 minutes                                                                |
| Weight (w/o Battery)  | 1675 g                                                              |
| Weight (w/ Battery)   | 3041 g                                                              |
| Imaging         | Gimbal-Mounted Flir Duo (IR and RGB) and Downward-Facing Intel Realsense D435 |
| Live Video      | Flir Duo, ~0.5 mile range, 5.8 GHz                                        |

## The Build
After configuring the *BlueBird* and ordering parts, the build process began. 
![picture](/assets/images/bluebird/bluebird_parts.JPEG)

I made the following wiring diagram to help place components with required electrical connections in mind.
![picture](/assets/images/bluebird/bluebird_wiring_diagram.jpg)

I designed a variety of custom 3D printed and laser cut parts for vibration dampening and mounting components.
![picture](/assets/images/bluebird/bluebird_custom_cad.jpg)

The power distribution board (PDB) supplies power to all four ESCs and regulates power to other components.
{% include gallery id="gallery2" %}

The Pixhawk 6C flight controller is secured with a custom vibration-damped mount on the top plate for ease of access, particularly when interfacing with the optional onboard Raspberry Pi for autonomous path planning.
![picture](/assets/images/bluebird/bluebird_pixhawk.JPEG)

I installed the motors, GPS unit, receiver, telemetry unit, and video transmitter/antenna.
![picture](/assets/images/bluebird/bluebird_weight.JPEG)

The *BlueBird* fits safely in a Pelican case for storage and transport.
![picture](/assets/images/bluebird/bluebird_case.JPEG)

## Flight Testing
The first *BlueBird* is shown below, ready for flight testing within a month following its conception. Even given time constraints from classes and other student competition teams, this type of fast-paced, hands-on work felt energizing and rewarding - especially after demonstrating a successful first flight. 
![picture](/assets/images/bluebird/bluebird_testing_2.JPEG)

In the following weeks, we conducted further flight testing without incident - a refreshing change from our old drone platform. I also assembled a second identical *BlueBird* (shown in the background of the photo below) for redundancy and to enable future testing with multiple drones. I thoroughly documented the build to ensure that future lab members could replicate the process and make additional *BlueBirds* as needed.
![picture](/assets/images/bluebird/bluebird_testing.JPEG)

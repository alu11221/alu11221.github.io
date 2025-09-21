---
title: "FEH Robot"
excerpt: "Built and programmed a 3-wheel omnidirectional robot."
layout: single
collection: projects
permalink: /projects/feh-robot/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/feh-robot/robot_teaser.PNG
  teaser: /assets/images/feh-robot/robot_teaser.PNG
author_profile: true
toc: true
toc_sticky: true
toc_label: "Jump to section"
toc_icon: "plane-departure"
classes: custom-font-size
order: 4

robot_intro:
  - url:        /assets/images/feh-robot/robot_splash_crop4by3.PNG
    image_path: /assets/images/feh-robot/robot_splash_crop4by3.PNG
  - url:        /assets/images/feh-robot/robot_13.JPEG
    image_path: /assets/images/feh-robot/robot_13.JPEG

course_2:
  - url:        /assets/images/feh-robot/course_2.JPEG
    image_path: /assets/images/feh-robot/course_2.JPEG

prototype:
  - url:        /assets/images/feh-robot/robot_1.JPEG
    image_path: /assets/images/feh-robot/robot_1.JPEG
  - url:        /assets/images/feh-robot/robot_2.JPEG
    image_path: /assets/images/feh-robot/robot_2.JPEG

robot_1:
  - url:        /assets/images/feh-robot/robot_3.JPEG
    image_path: /assets/images/feh-robot/robot_3.JPEG
  - url:        /assets/images/feh-robot/robot_4.JPEG
    image_path: /assets/images/feh-robot/robot_4.JPEG

robot_2:
  - url:        /assets/images/feh-robot/robot_5.JPEG
    image_path: /assets/images/feh-robot/robot_5.JPEG

robot_3:
  - url:        /assets/images/feh-robot/robot_6.JPEG
    image_path: /assets/images/feh-robot/robot_6.JPEG
  - url:        /assets/images/feh-robot/robot_7.JPEG
    image_path: /assets/images/feh-robot/robot_7.JPEG

robot_4:
  - url:        /assets/images/feh-robot/robot_11.JPEG
    image_path: /assets/images/feh-robot/robot_11.JPEG

robot_5:
  - url:        /assets/images/feh-robot/robot_10.JPEG
    image_path: /assets/images/feh-robot/robot_10.JPEG

jukebox:
  - url:        /assets/images/feh-robot/jukebox_1.JPEG
    image_path: /assets/images/feh-robot/jukebox_1.JPEG
  - url:        /assets/images/feh-robot/robot_8.JPEG
    image_path: /assets/images/feh-robot/robot_8.JPEG

tray_1:
  - url:        /assets/images/feh-robot/tray_2.JPEG
    image_path: /assets/images/feh-robot/tray_2.JPEG
  - url:        /assets/images/feh-robot/tray_3.JPEG
    image_path: /assets/images/feh-robot/tray_3.JPEG

tray_2:
  - url:        /assets/images/feh-robot/tray_4.JPEG
    image_path: /assets/images/feh-robot/tray_4.JPEG

icecream:
  - url:        /assets/images/feh-robot/ice_cream.JPEG
    image_path: /assets/images/feh-robot/ice_cream.JPEG

burger_1:
  - url:        /assets/images/feh-robot/burger_3.JPEG
    image_path: /assets/images/feh-robot/burger_3.JPEG
  - url:        /assets/images/feh-robot/burger_4.JPEG
    image_path: /assets/images/feh-robot/burger_4.JPEG

burger_2:
  - url:        /assets/images/feh-robot/burger_2.JPEG
    image_path: /assets/images/feh-robot/burger_2.JPEG

ticket_1:
  - url:        /assets/images/feh-robot/ticket_4.JPEG
    image_path: /assets/images/feh-robot/ticket_4.JPEG
  - url:        /assets/images/feh-robot/ticket_5.JPEG
    image_path: /assets/images/feh-robot/ticket_5.JPEG

ticket_2:
  - url:        /assets/images/feh-robot/ticket_1.JPEG
    image_path: /assets/images/feh-robot/ticket_1.JPEG
  - url:        /assets/images/feh-robot/ticket_2.JPEG
    image_path: /assets/images/feh-robot/ticket_2.JPEG

---

## Intro
Every year, the Fundamentals of Engineering for Honors (FEH) program at OSU hosts a robot competition for first-year engineering students. ~60 teams of four students each are tasked with making an autonomous robot complete a set of tasks on a course built by the TAs. The more tasks completed and the less time it takes, the more points awarded. 

**Timeline:** February 2020 - April 2020

{% include gallery id="robot_intro" %}

## My Role
I was assigned to a team of three students rather than the usual four, but what we lacked in heads, we made up for in drive. I was particularly excited about the project and spearheaded the design and programming of the robot. While I led many of the technical efforts, our success was a result of continuous collaboration and shared determination among the team. 

I had so much fun with this project, and looked up to a lot of the TAs for all the work they had put into making the robot course. In a large part, this project inspired me to become a TA in the FEH program, which I continued throughout the rest of my time at school.

## Constraints & The Course
Each team was given a budget of $160, and could only select from a limited parts list available in the program. The robots were required to be autonomous and used the [FEH *Proteus*](https://u.osu.edu/fehproteus/) microcontroller, programmed in C++ with built-in motor speed controllers and I/O for sensors and servos. 

The TAs put together a diner-themed course for the 2020 robot competition. It involved tasks such as placing a tray in the sink, operating a soft serve machine, and flipping burgers.

We began by developing a high-level strategy for how to most efficiently move through the course while scoring all available points.

{% include gallery id="course_2" caption="Birds-eye view of the diner-themed course. Our planned strategy drawn in pink." %}

## Configuration
Despite the slightly greater complexity, we chose a 3-wheel robot using omnidirectional wheels. This allowed us to improve our speed on the course by combining translational and rotational motion.

We built a cardboard mockup to check the fit and placement of components, giving us confidence in our high-level design before starting to build the actual robot.

{% include gallery id="prototype" caption="Cardboard mockup to check fit & placement of components." %}

## The Build
I designed the chassis to be a hexagonal box with tabs for easy part alignment and a removable top lid for access to electronics inside. The parts were laser cut out of 1/4" MDF and assembled with wood glue. The resulting chassis was robust and easy to work with.

{% include gallery id="robot_1" caption="Parts were laser-cut for precision and ease of construction." %}
{% include gallery id="robot_2" %}
{% include gallery id="robot_3" caption="Installed motors and omnidirectional wheels on the bottom of the chassis." %}

## Navigation
We chose to use multiple methods of navigation, as each had their strengths and drawbacks. This proved to be useful, as we were able to utilize them together for efficient and accurate navigation. For example, we could: bump & align with a known wall, dead reckon until desired line detected, follow line until sensing a red or blue light, check position with RPS, refine position if out of tolerance, then perform the task knowing we are exactly where we want to be.

| Navigation Method | Description |
|-------------------|-------------|
| Dead Reckoning    | Simplest, but least reliable. Only used to save time while traveling short distances. |
| Bump Switches     | Simple and reliable - bump into and align with walls. Required a large flat surface nearby. |
| Line Following    | Three IR sensors used to follow lines. Only certain parts of the course had lines available. |
| Robot Positioning System (RPS) | Overhead camera used to track QR code on top of robot. Useful for refining position, but slower than other navigation methods due to latency and the move/check/repeat algorithm. |

{% include gallery id="robot_4" caption="Top view showing QR code used for RPS and one side bump switch." %}
{% include gallery id="robot_5" caption="Bottom view showing line following sensors and the two front bump switches." %}

## Tasks & Mechanisms
We kept our mechanisms simple, avoiding complexity and prioritizing reliability.

### Jukebox
The robot had to detect the color (red/blue, set randomly) of an LED built into the floor of the course, then push the corresponding button on the jukebox to play the correct song.

{% include gallery id="jukebox" caption="Photocell detects LED color, then robot presses corresponding jukebox button." %}

### Food Tray
Each robot started with one red food tray, which it had to either place in the sink or on top of the trash can.

{% include gallery id="tray_1" caption="Tray mechanism, fully retracted and fully extended." %}
{% include gallery id="tray_2" caption="Our robot dropping the tray into the sink." %}

### Ice Cream
Each robot was sent a randomized signal through RPS indicating vanilla, chocolate, or twist soft-serve ice cream. The robot then had to flip the correct lever down, leave it down for at least 7 seconds, then flip it back up.

{% include gallery id="icecream" caption="The same mechanism used for the tray is used here as well." %}

### Burger Flip
The robot had to flip a burger at the grill station. There were a few ways to do this, but we chose to rotate the mechanism using a dedicated servo and simple 3D printed prongs.

{% include gallery id="burger_1" caption="Simple burger flip mechanism." %}
{% include gallery id="burger_2" %}

### Order Ticket
The robot had to slide an order ticket to signal the completion of an order. The ticket was recessed behind a wall, so we needed a dedicated arm to reach it.

{% include gallery id="ticket_1" caption="Ticket slider arm, extended vs. retracted." %}
{% include gallery id="ticket_2" caption="The robot extends the arm, aligns with the walls, then slides the ticket." %}

## Results
Unfortunately, the competition was canceled due to COVID. However, our team was well-positioned leading up to competition; we were 1 of 2 teams to successfully complete the course before campus was closed. Of those two teams, our robot was significantly faster. 

Even though we didn't get to competition day, I still enjoyed this project so much that I became a TA in the FEH program for the rest of my time in undergrad, helping run classes and competitions for the next generation of Buckeye engineers.

## Video
See our robot in action. This test run was filmed the day before spring break, after which campus was closed due to COVID.

<iframe width="560" height="315" src="https://www.youtube.com/embed/lHj338RlukA?si=QaDHCz4V7gEu_DSl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
---
layout: project
type: project
image: images/sdvxcap.jpg
title: Arduino SDVX Project
permalink: projects/sdvx
# All dates must be YYYY-MM-DD format!
date: 2017-08-01
labels:
  - Arduino
  - GitHub
  - C++
  - HID
  - WINE
summary: An Arduino adaptation of a Sound Voltex Controller.
---
<img src="../images/inprog.jpg" width="600">

Sound Voltex/K-Shoot Mania is a rhythm game which originated in Japan. Motivated by the high cost of commercial gamepads, I set out to create a DIY version. For this particular revision, I decided to be liberal with the design and substitute the main buttons with 33mm buttons (original 60mm).

The current software design is built for the open-source version of SDVX, K-Shoot mania. Further designs will include persistent setting storage and increased compatibility with b***** tools. The SDVX application tools will also be attempted to be ported to Debian via wine.

While this current project is ongoing, I was able to apply several skills which I have acquired over the years. For the initial frame, I utilized a 3D printer to print small scale prototype boxes. For the electronics, I had to solder components onto protoboard to test both hardware and software based debounce. Programming for the controller is still ongoing and will make use of 3rd party libraries.

The source code for the firmware can be found [here](https://github.com/Reyn-Mukai/Bemani-SDVX).

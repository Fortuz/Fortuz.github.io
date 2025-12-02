---
title: "Mecanumbot project"
layout: single
toc: true
toc_label: "On This Page"
toc_sticky: true
sidebar:
  nav: mecanumbot
permalink: /docs/mecanumbot_main/
---

## Overview

The Mecanumbot is a Turtlebot3 friend concept. Using mechanum wheel drive system and mounted with extra motors like the grabber and the camera moving motor. Due to the hardware changes the original Turtlebot3 code was modified and improved. Low level hardware components like the OpenCR microcontroller code were changed andan additional Srduino Nano microcontroller were added to handle the LEDs on the robot back. The Camera was elevated to provide a better view angle and to not block the LIDAR. The extra mounts are 3D printed.

The original [Turtlebot3 documentation](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/) can be seen here. 

## Assembly Instructions

Content is coming soon.

Schematics

![Nano and LED connection schematic](/assets/images/mecanumbot/Nano_Led_schematic.png)

stb

![OpenCR and Motor schematic](/assets/images/mecanumbot/OpenCR_Motor_schematic.png)

stb

![Raspberry Pi and USB schematic](/assets/images/mecanumbot/RaspberryPi_USB_schematic.png)

stb

![Network architecture schematic](/assets/images/mecanumbot/Network_architecture.png)
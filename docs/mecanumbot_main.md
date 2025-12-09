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

<p style="text-align: justify;">
The Mecanumbot is a Turtlebot3 friend concept. Using mechanum wheel drive system and mounted with extra motors like the grabber and the camera moving motor. Due to the hardware changes the original Turtlebot3 code was modified and improved. Low level hardware components like the OpenCR microcontroller code were changed and an additional Arduino Nano microcontroller were added to handle the LEDs on the robot back. The Camera was elevated to provide a better view angle and to not block the LIDAR. The extra mounts are 3D printed.
</p>

The original [Turtlebot3 documentation](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/) can be seen here. 

The project is currently developed in ROS2 Humble.

<p align="center">
  <img src="https://github.com/Fortuz/mecanumbot/raw/main/docs/images/mecanumbot.jpg" 
       alt="Mecanumbot image" 
       style="max-width:500px;">
</p>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <a href="/" class="btn btn--primary">Home</a>
  <a href="/docs/mecanumbot/hardware_assembly/" class="btn btn--primary">Next Page</a>
</div>
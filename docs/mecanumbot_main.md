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

## Repository summary

| Repository | Description | State |
|------------|-------------| ------|
| [Fortuz.github.io](https://github.com/Fortuz/Fortuz.github.io) | Source code for the webpage documentation | Ready |
| [mecanumbot](https://github.com/Fortuz/mecanumbot) | Main ROS2 package for the Mecanumbot robot installed on the onboard Raspberry Pi | Ready |
| [mecanumbot_microcontrollers](https://github.com/Fortuz/mecanumbot_microcontrollers) | Modified OpenCR microcontroller code to use with the ROS2 main code. Standalone OpenCR code for just gamepad conrol. Arduino Nano code for controlling the LEDs.  | Ready |
| [mecanumbot_remote](https://github.com/Fortuz/mecanumbot_remote) | ROS2 packages to be installed on a remote PC to control the robot via WiFi. | Ready |
| [mecanumbot_msgs](https://github.com/Fortuz/mecanumbot_msgs) | Message definitions used in the Mecanumbot architecture. Can be installed on the robot and the remote PS as well. | Ready |
| [mecanumbot_observer](https://github.com/Fortuz/mecanumbot_observer) | ToDo | Not tested |
| [mecanumbot_camera](https://github.com/Fortuz/mecanumbot_camera) | ToDo | Not tested |
| [basler_camera](https://github.com/Fortuz/basler_camera) | ToDo | Not tested |
| [mecanumbot_gui](https://github.com/Fortuz/mecanumbot_gui) | ToDo | Not tested |
| [mecanumbot_simulations](https://github.com/Fortuz/mecanumbot_simulations) | ToDo | Empty |


<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <a href="/" class="btn btn--primary">Home</a>
  <a href="/docs/mecanumbot/hardware_assembly/" class="btn btn--primary">Next Page</a>
</div>


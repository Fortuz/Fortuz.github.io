---
title: "Mecanumbot project"
layout: single
toc: true
toc_label: "On This Page"
toc_sticky: true
sidebar:
  nav: mecanumbot
permalink: /docs/mecanumbot/hardware_assembly/
---

## Hardware assembly

<p style="text-align: justify;">
The Mecanumbot base is a modified Turtlebot3 Waffle with 2 additional driving motors and 3 additional actuator motors. The extra parts to mount the actuator motors and the LEDS are 3D printed. The build also utilize parts from the Robotis Bioloid Premium kit like the grabbers.
</p>

### Nano - LED connections

<p style="text-align: justify;">
The Arduino Nano only task is to control the LEDs mounted on the Mecanumbot. 
</p>

The used LEDs type: WS2812B - [Datasheet](https://www.alldatasheet.com/datasheet-pdf/pdf/1179113/WORLDSEMI/WS2812B.html)

Schematic of the wireing can be seen below.

![Nano and LED connection schematic](/assets/images/mecanumbot/Nano_Led_schematic.png)

### OpenCR - Motor connections

<p style="text-align: justify;">
The OpenCR is responsible for contorlling the motor, provinding power supply for the Raspberry Pi and housing the IMU sensor. 

AX-12A Dynamixel motors are used to move the grabbers and the camera and XM430-W210 Dynamixel motors are used in the drive system.  
</p>

[AX-12A motor specification](https://emanual.robotis.com/docs/en/dxl/ax/ax-12a/)

[XM430-W210-T motor specification](https://emanual.robotis.com/docs/en/dxl/x/xm430-w210/)


![OpenCR and Motor schematic](/assets/images/mecanumbot/OpenCR_Motor_schematic.png)

<p style="text-align: justify;">
Since the motors operate on 12V the whole system is powered through the OpenCR either using a 12V Battery or 12V power supply.
</p>

**Tip**: A RC100 Bluetotth receiver is pluged to the OpenCR from the original Turtlebot3 setup. This is an alternative option to control the robot if the corresponding OpenCR firmwhare is uploaded.
{: .notice--info}

### Raspberry Pi - Microcontroller connections

<p style="text-align: justify;">
On the Mecanumbot the main onboard computing unit is a Raspberry Pi 3B+. The Arduino Nano and the OpenCR board connected to the Raspberry Pi via USB. Also the LIDAR and the Pi Camera connected directly to the Raspberry Pi.
</p>

![Raspberry Pi and USB schematic](/assets/images/mecanumbot/RaspberryPi_USB_schematic.png)

## Concept

<p style="text-align: justify;">
The main concept with the robot builds up like this: The OpenCR board controlls the motors, provides power supply and integrates additional sensors and actuators like the IMU and beeper. The Arduino Nano controls the LEDs. The Raspberry Pi serves as the main onboard computational unit running ROS2 Humbla. The Raspberry Pi connects to a router wirelessly and through this router a remote computr could be used to observ the robot and provide extra computational resources for the advanced tasks. The development workflow also can be done using SSH connection.
</p>

![Network architecture schematic](/assets/images/mecanumbot/Network_architecture.png)

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <a href="/docs/mecanumbot_main/" class="btn btn--primary">Previous Page</a>
  <a href="/docs/hardware_assembly/" class="btn btn--primary">Next Page</a>
</div>


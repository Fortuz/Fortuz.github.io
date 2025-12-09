---
title: "Mecanumbot project"
layout: single
toc: true
toc_label: "On This Page"
toc_sticky: true
sidebar:
  nav: mecanumbot
permalink: /docs/mecanumbot/microcontroller_codes/
---

## Microcontroller codes

### Workflow setup

<p style="text-align: justify;">
Arduino IDE is used to develop, inspect and upload the microcontroller source codes.
</p>

[Download Arduino IDE](https://www.arduino.cc/en/software/)

<p style="text-align: justify;">
The corresponding git repository was designed to be cloned into the Arduino Sketch folder.
</p>

```bash
cd  ~/Documents/Arduino
git clone https://github.com/Fortuz/mecanumbot_microcontrollers.git
```

<p style="text-align: justify;">
If cloned sucesfully the microcontroller codes should appear in the Arduino IDE.
</p>

![Arduino sketch option](/assets/images/general/arduino_sketch.png)

<p style="text-align: justify;">
Port, Board and Bootloader options should be set according to the different boards before uploading the codes.
</p>

<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <a href="/docs/mecanumbot/hardware_assembly/" class="btn btn--primary">Previous Page</a>
  <a href="/docs/mecanumbot/hardware_assembly/" class="btn btn--primary">Next Page</a>
</div>
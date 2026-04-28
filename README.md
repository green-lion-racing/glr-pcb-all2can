# glr-pcb-all2can

This is a KiCad PCB repository for the [All2Can](https://github.com/green-lion-racing/glr-all2can) software.

<div align="center">
  <img src="img/glr-pcb-all2can-front-smd.png" width="49%" />
  <img src="img/glr-pcb-all2can-back.png" width="49%" />
</div>
<div align="center">
  <img src="img/glr-pcb-all2can-front.png" width="49%" />
</div>

## Overview

This PCB is intended to collect sensor data and provide that to can.

The connector is D-Sub 15-pin male.  
It supports a 24V power supply voltage.  
One CAN (up to 5 MB/s) connection.  
Uses a `STMSTM32C092KCT6` microcontroller (250kbytes Flash 36kbytes Ram).  
It also preserves space for an 6-axis IMU `LSM6DSV16BXTR`.  

There are 7 analog/digital inputs (input voltage level is configurable by a voltage divider).  
And 4 digital outputs (5V level).

Provides headers for SPI, I2C, UART.

## History

This PCB is actually the fourthst generation of this type used for our team.

1. [Frist version](https://circuitmaker.com/Projects/Details/Pat-Her/All2Can-V01) in CircuitMaker.  
   By [PatHer777](https://github.com/PatHer777).

2. [Second version](https://circuitmaker.com/Projects/Details/Jannis-Dohm/All2Can) also in CircuitMaker with some changes.  
   By Jannis Dohm.

3. Third in Fusion 360, with new PCB design.  
   By Alexander Wallrodt.

4. Now [fourth version](https://github.com/green-lion-racing/glr-pcb-all2can) in KiCad, with some changes to schematic and smaller PCB.  
   By Alexander Wallrodt.

## How to use this template

You can use this template by clicking on this [link](https://github.com/new?owner=green-lion-racing&template_name=glr-pcb-template&template_owner=green-lion-racing) or clicking the button `Use this template`. And set your repository name to `glr-pcb-your-project-name`.

This is a list of task you should first do when using this template:

- [x] Rename every occurence of `glr-pcb-template` to `glr-pcb-your-project-name`. Occurence of this string are found here:
  
  - Project files e. g. `glr-pcb-template.kicad_pcb`, `glr-pcb-template.kicad_pro`, and `glr-pcb-template.kicad_sch`.
  
  - Title of this `README.md` file.
  
  - Images in `img/` and its references in `README.md`.
  
  - Inside of files `glr-pcb-template.kicad_pro` find the line with `glr-pcb-template` and change to `glr-pcb-your-project-name`.

- [x] Change short description and longer overview of this board in `README.md`.

- [x] Replace display images in `img/` used in `README.md` of a rendering of your pcb.

- [ ] Fill out used parts table in `README.md`.

Remove this template guide when everything is changed. 

## Used parts

| Article | Description | Perma-Link | Quantity |
| ------- | ----------- | ---------- | -------- |
|         |             |            |          |

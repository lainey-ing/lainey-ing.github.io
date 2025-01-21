---
title: "Syringe Pump"
excerpt: "This project uses custom 3D printed parts along with different mechanical and electrical components to create a highly accurate automated syringe pump that extrudes fluids at a specified flow rate."
header:
  image: /assets/img/SyringePump.jpg
  teaser: /assets/img/SyringePump.png
gallery:
  - url: /assets/img/RunningSyringePump.jpg
    image_path: assets/img/RunningSyringePump.jpg
    alt: "running syringe pump"
---

For a class project we were tasked with creating a DIY syringe pump using only 3D printed components and provided parts. It is compatible with syringes of different diameters (20 mL to 10 mL). The pump is driven by a stepper motor coupled to a lead screw, and the flow rate is easily adjustable using an Arduino program, and can be set in mL/min for two different syringe diameters. It is also designed to have an LED that is green when running, yellow when paused, and red when out of liquid. A switch button was also included to automatically stop the plunger once it has fully dispensed liquid, and a pause button is included to momentarily halt it.

* Operating Instructions
  * Insert a filled syringe into the syringe handle and tip holder 
  * Input the desired flow rate and the size of the syringe.
  * Press the power button on the side of the enclosure. The LED light will turn green and the carriage will push the plunger forward.
  * In the need to pause the plunger mid-way through the linear range of motion, press the power button to pause indefinitely.
  * The motion will terminate once the limit switch is hit, signaling that the syringe is out of fluid.

Arduino Code: https://docs.google.com/document/d/10CzmRPEOwFuH_D_E06-ETulo9I3_1qdl7hjgF0dHmrM/edit?tab=t.szlb81wgwdag

{% include gallery caption="This is a sample gallery to go along with this case study." %}

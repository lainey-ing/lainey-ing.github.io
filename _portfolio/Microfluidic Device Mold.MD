---
title: "Microfluidic Device"
excerpt: "A chip designed to sort particles using Pinch Flow Fractionation (PFF)."
header:
  image: /assets/img/fluidicdevicemodel.png
  teaser: /assets/img/fluidicdevicemodel.png
gallery:
  - url: /assets/img/fluidicdevicemodel.png
    image_path: assets/img/fluidicdevicemodel.png
    alt: "model of the microfluidic device"
---

This project uses high resolution resin printing and CAD modelling to design and create a mold for a microfluidic device capable of sorting particles within a range of 125-150 µm and 425-500 µm. A mold will be designed in Fusion 360, printed using a Form 4 SLA printer, cast with polydimethylsiloxane (PDMS), and sealed with a substrate.
A microfluidic device is an instrument that uses small amounts of fluid on a microchip to do tests with. Pinch Flow Fractionation is one method of sorting small particles into different channels based on their size using laminar flow profiles. This kind of particle sorting is mainly used in biomedical applications, such as for seperating cells or blood components, though it can also be used in environmental monitoring to detect pollution in waterways.
# CAD Modeling
### Design Specifications:
* The device, when molded, must be precisely 25 mm wide by 75 mm long
* The aspect ratio must be less than 4:1, i.e. the height of any feature must be now greater than 4 times its width.
* For inlets and outlets a 1.5 mm post should be extruded above the top of the mold, this will create a hole that is compatible with the microfluidic barb
* Inlets or outlets must be at least 11 mm away from each other
* Channels must be at least 3 mm away from the edge of the device
* There should be no features that cannot be demolded (cutbacks or small holes)
* Features smaller than 85 µm cannot be printed
## Final Model:
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a40233dd030de6042f?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Printing and Curing
The mold was printed using a FormLabs Form 3+ resin printer with High Temp V2 resin. After printing, the device was rinsed of uncured resin in isopropyl alcohol (IPA), for 10 minutes, then was dried for 30 minutes. It was then placed in the Form Cure for curing. The Form Cure exposes printed parts to UV light to stabilize them and improve their final mechanical properties. After 60 minutes of curing, the support material was removed and the mold was complete.

# Final Device
To go from the mold to the final device,

---
title: "Multimaterial Pliers"
excerpt: "Filament 3D printed pliers capable of gripping and picking up small objects."
header:
  image: /assets/img/Pliers.jpg
  teaser: /assets/img/Pliers.jpg
gallery:
  - url: /assets/img/Pliers.jpg
    image_path: assets/img/Pliers.jpg
    alt: "Multimaterial 3D printed Pliers"
---

This project uses print-in-place parts to create a functional pair of pliers. The pliers are to be printed out of a rigid, sturdy plastic to make up the handles and jaws, while the center is printed with an elastic component, allowing the jaws to close when squeezing the handles. Certain materials are known to work together better than others, even with differing mechanical properties. Common combinations are PLA and TPU, PLA and PVA, and ABS and HIPs. I printed with PLA and TPU for this project. 

# CAD Model:
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4f7f2fb57e6dd7ff3?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Design Specifications
The handles are 90 mm long and the jaws are 45 mm. The jaws have a 6 by 14 mm area of surface to grip objects, and can hold objects with a width up to 10mm. The jaws and handles are made of PLA. The center connecting piece was printed out of TPU. In the CAD model the center piece is a solid block, but by altering the print settings a more functional design can be created.

By removing the solid layers from the print a more flexible piece can be printed. The flexibility can be further adjusted by changing the percentage of infill, for my design I used 15% infill. 

<img src="/assets/img/printsettings.png" alt="Settings for printing flexible center piece." style="width:300px;"/>

# Final Product
<img src="/assets/img/Pliers.jpg" alt="Multimaterial 3D printed Pliers" style="width:250px;"/>

<img src="/assets/img/pliersgif.gif" alt="Pliers opening and closing." style="width:200px;"/>



{% include gallery caption="." %}

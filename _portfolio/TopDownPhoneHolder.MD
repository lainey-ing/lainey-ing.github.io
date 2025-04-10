---
title: "Bike Phone Holder"
excerpt: "A FFF and pSLS printed device to hold a phone and attach to a bike handle."
header:
  image: /assets/img/fluidicdevicemodel.png
  teaser: /assets/img/fluidicdevicemodel.png
gallery:
  - url: /assets/img/fluidicdevicemodel.png
    image_path: assets/img/fluidicdevicemodel.png
    alt: "model of the microfluidic device"
---

This project uses a top-down modeling approach to design a phone holder that can attach to a bike or scooter handle. The device also contains a detent mechanism, allowing the phone to be rotated to a landscape or portrait position while remaining attached to the bike.

## CAD Modeling
A 'top-down' modeling approach was used in the CAD design process, meaning that each component of the design was built within the main assembly, rather than being imported from a different file. 

The design process started with a model of the handlebars that remains anchored in place. From there, the attachment to the handlebars, the detent mechanism, and the phone case could be built around the bars. This design approach focuses on the relationships between each component rather than the components themselves, this makes it easier to adjust components if something needs to be changed. It can be difficult and time consuming to make the same changes in bottom-up modeling, because each component has to be adjusted individually and reimported into the model. 

Another useful feature of top-down modeling is the ability to make as-built joints. As stated earlier, each component was built around the handle bars in the position it would be in on the final model. This means the bodies can be jointed together exactly where they need to be, allowing accomodation for clearance or changes to the design.

The detent mechanism utilized a ball bearing and spring to put pressure on the phone case while still allowing it to roll on the ball with less friction. On the phone case, 3 small holes were indented that the ball could fall into. In those 3 locations the phonecase requires more force to be turned out of place, until the ball rolls into another space, putting the phone in a new orientation. 
The ball and spring mechanism is enclosed by a larger housing that could be screwed to the attachment to the handlebars. The housing is designed to prevent the phonecase from moving forwards or backwards, only allowing it to rotate in place. This required it to be powder printed. I also chose to powder print the detent mechanism because of the better mechanical properties of the powder when compared to filament printing; pSLS prints are less prone to breaking due to shear forces, making it the ideal choice for the detent mechanism.
For the phonecase, I combined pSLS and FFF printing. The filament printed aspect of the phonecase was printed out of TPU. The flexible material makes it easy to attach the phone to the holder, while the powder printed aspect keeps it securly in place. I also printed the handle bar attachment out of TPU because I thought it would grip the handlebars better and be less likely to slip.

<img src="/assets/img/detentsectionview.png" alt="Section View of the detent mechanism with ball bearing and spring." style="width:300px;"/>

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4d0916f18dfaca541?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<img src="/assets/img/bikephoneholderr.png" alt="Bike phone holder render." style="width:300px;"/>

# Completed Device:

<img src="/assets/img/fullbikephonecase.jpg" alt="Completed bike phone case." style="width:300px;"/>


To use the device, simply screw the handlebar attachment around the handle bar and put your phone into the phone case. It can remain in the portrait orientation or turned left or right to landscape.

<img src="/assets/img/IMG-1837.gif" alt="Completed bike phone case moving into the three orientations." style="width:300px;"/>

## Components
Top Half of the phone case, printed with TPU:

<img src="/assets/img/topphonecase.jpg" alt="Top half of the phone case." style="width:300px;"/>

Detent mechanism and bottom half of the phone case, powder printed:

<img src="/assets/img/detentrr.png" alt="Detent Mechanism and bottom half of the phone case." style="width:300px;"/>

Housing for the detent mechanism, powder printed:

<img src="/assets/img/housingr.png" alt="Housing for the detent mechanism." style="width:300px;"/>

Handlebar attachment, printed with TPU:

<img src="/assets/img/handleattachment.jpg" alt="Bike handlebars grip." style="width:300px;"/>

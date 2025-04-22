---
title: "Headphones Stand"
excerpt: "A pSLS printed headphones stand modelled using Generative Design"
header:
  image: /assets/img/fullbikephonecase.jpg
  teaser: /assets/img/fullbikephonecase.jpg
gallery:
  - url: /assets/img/fullbikephonecase.jpg
    image_path: assets/img/fullbikephonecase.jpg
    alt: "Completed bike phone case."
---

This project uses Fusion 360's generative design capabilities to model a lightweight headphones stand. The stand supports the weight of the headphones, and contains a small housing for an airpods case. It also has features to hold cords so the headphones and airpods can charge while they're not being used.

The final model ended up weighing 0.125kg, lighter than most found online, which typically weighed between 0.5-1.5kg. 

## CAD Modeling
When modeling the stand, I started with the perserve geometries. Since the stand has the rest on a desk or shelf, the first perserved geometry was a round base for the COMPUTER---- to build off of. It had to be wide enough to not fall over when experiencing weights of at least 0.26kg, as this is the weight of the headphones. 

Next I made the support for the headphones. I made a curved space for the headband to sit on, with short barriers on either side to keep it from sliding off. On the support, I added 3 different forces to simulate how the stand would be used. A regular downward force to represent the weight of the headphones, an angled force to represent the headphones being set down, and a moment around the center to simulate the headphones being placed off-center. This combination of forces ensures that Fusion will generate enough support material to keep the stand from collapsing under the weight of the headphones.

I also added a small compartment in the center to house airpods. The space also includes a space to hold a charging cord, and 3 walls to keep the airpods from falling off. Similarly to the headphones support, I included a force straight down and at an angle to represent the airpods sitting in place and being set down.

The values associated with the applied forces were calculated based on the weight of the headphones. The headphones weigh 260 grams, and the airpods weigh 5.7 grams. These weights equate to 2.55 and 0.56 Newtons respectively.

I decided to create a headphones stand because right now my headphones sit on my desk and take up space when I'm not using them. My design improves on stands that could be bought since its a lighter weight and includes a space to house airpods or another device.


Before using the generative design feature, I also had to model the obstacle geometries. 2 obstacle geometries included the headphones and airpods themselves. I also wanted to avoid the front of the stand having any material, so that they could easily be put down. I also included a few spaces where cords could be held, so obstacle geometries were put around those loctions aswell.

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

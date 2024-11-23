---
title: "Bike Phone Mount"
excerpt: "Top-Down Modeling - Phone Mount for Bikes"
header:
  teaser: assets/img/BikePhoneMount.jpg
gallery:
  - image_path: assets/img/MountPrototypes.jpg
  - image_path: assets/img/BikePhoneMount.jpg
---
---

## Project Description

Top-down modeling is a design approach where the overall structure or assembly is defined first, and individual components are designed within this framework. For this project, the top-down method was leveraged by importing handlebars and a CAD model of the phone as references. These elements drove the design process, ensuring the holder's components were modeled in place for an accurate fit. Using as-built joints, the parts were assembled directly in the CAD environment. This helped maintain alignment and quickly ensure dimensional accuracy. The top-down method allowed for a cohesive and efficient design process, with each part tailored to the bike handlebars and phone dimensions.

<br>

## CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a463a6ee0857e66c84?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<br>

## Design

This comprehensive top-down modeling project required intentional prototyping from beginning to end in areas like mechanism design, assembly process, and material choice

###### Description & Rationale
The first design criteria was ensuring that the device could securely grip 23-25 mm handlebars. To achieve this, a 25 mm circular piece was modeled with a 1 mm offset in between pieces. Rectangular pieces with 6 mm holes jutted out to the side, allowing space for screws that tighten the mount's grip on the handlebars. The bottom piece was manufactured out of TPU 95A to prevent cracking when the screws are tightened. 
<br>

From the top piece of the handlebar grip, an arm was extended upwards approximately 80 mm at a 70 degree angle. This segment was manufactured out of ABS due to its strength and moderate flexibility compared to PLA. This material selection was key for this piece as well as the second design criteria. The holder must be able to lock the phone in a vertical or horizontal orientation, which can be changed at any point during a ride. Additional degrees of freedom are optional, but I decided to include them in the design. 
<br>

The extended arm connects directly to the detent mechanism. This mechanism is a hollow circular piece with small arches cut out of the edge in a rotationally symmetric pattern. The back of the piece that grips the phone has an opposing circular piece that fits inside and has similar but smaller arches circling its outer edge. This conjunction of pieces is called a detent mechanism and allows the phone to lock in place at various locations when twisted due to a slight give in the material when force is applied. The length and radius of the arches were rapidly prototyped at varying dimensions until the perfect fit was achieved. 
<br>

The last design criteria was modeling a phone grip that allowed access to all charging ports and buttons while providing quick and easy phone insertion. I opted for an 'X' shape with small grips at each corner that securely hold the phone in place. This piece was manufactured out of TPU not only to allow some stretching to insert the phone but also for the detent mechanism to have some give when attempting to rotate.

###### Assembly
The assembly was quite simple due to how each component of the mount was designed. As previously mentioned, the piece that grips that handle bar was attached with a screw and nut on each side. The bottom piece was manufactured out of TPU to allow for strong tightening of the screws without cracking on the handlebar. Additionally one 6mm hole was modeled directly through the center of the phone grip, detent mechanism, and extension arm. Slightly larger holes of 10mm and 13m were modeled on each end to allow space for the bolt head and nut.
<br>

## Results

{% include gallery caption="Prototyping Process & Final Phone Mount" %}


## Detent Mechanism in Action!

![Rotation in Action](/assets/img/DetentGIF.gif)


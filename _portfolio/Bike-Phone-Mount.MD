---
title: "Bike Phone Mount"
excerpt: "Top-Down Modeling - Phone Mount for Bikes"
header:
  teaser: assets/img/Pliers.png
gallery:
  - image_path: assets/img/Pliers.png
---
---

## Project Description

Top-down modeling is a design approach where the overall structure or assembly is defined first, and individual components are designed within this framework. For this project, the top-down method was leveraged by importing handlebars and a CAD model of the phone as references. These elements drove the design process, ensuring the holder's components were modeled in place for an accurate fit. Using as-built joints, the parts were assembled directly in the CAD environment. This helped maintain alignment and quickly ensure dimensional accuracy. The top-down method allowed for a cohesive and efficient design process, with each part tailored to the bike handlebars and phone dimensions.

<br>

## CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a463a6ee0857e66c84?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<br>

## Design Description

This comprehensive top-down modeling project required intentional prototyping from beginning to end in areas like mechanism design, assembly process, and material choice

###### Design Rationale
The first design criteria was ensuring that the device could securely grip 23-25 mm handlebars. To achieve this, a 25 mm circular piece was modeled with a 1 mm offset in between pieces. Rectangular pieces with 6 mm holes jutted out to the side, allowing space for screws that tighten the mount's grip on the handlebars. The bottom piece was manufactured out of TPU 95A to prevent cracking when the screws are tightened. From the top piece of the handlebar grip, an arm was extended upwards approximately 80 mm at a 70 degree angle. This segment was manufactured out of ABS due to its strength and moderate flexibility compared to PLA. This material selection was key for the second design criteria. The holder must be able to lock the phone in a vertical or horizontal orientation, which can be changed at any point during a ride. Additional degrees of freedom are optional, but I decided to include them in the design. The extended arm connects directly to the detent mechanism. This mechanism is a hollow circular piece with small arches cut out of the edge in a rotationally symmetric pattern. The back of the piece that grips the phone has an opposing circular piece that fits inside and has similar but smaller arches circling its outer edge. This conjunction of pieces is called a detent mechanism and allows the phone to lock in place at various locations when twisted due to a slight give in the material when force is applied. The length and radius of the arches were rapidly prototyped at varying dimensions until the perfect fit was achieved. The last design criteria was modeling a phone grip that allowed access to all charging ports and buttons while providing quick and easy phone insertion. I opted for an 'X' shape with small grips at each corner that securely hold the phone in place. This piece was manufactured out of TPU not only to allow some stretching to insert the phone but also for the detent mechanism to have some give when attempting to rotate.

###### Assembly
The center piece was modeled as a filled-in square in Fusion360, then the spring grid lines were created in SuperSlicer. By utilizing a rectilinear infill pattern with low density, the spring could be quickly prototyped and edited. This piece was 3D printed using TPU 95a, which allowed for the flexibility of the piece when pinched on by the handles. After a few iterations, a slightly higher perimeter shell count with a rectilinear infill density of 8.5% yielded the best results.

<br>

## Printer/Sclicer Settings

| Setting         | Result                                |
|-----------------|---------------------------------------|
| Infill Density  | 20% (handles/grips), 8.5% (spring)    |
| Nozzle Diameter | 0.6 mm                                |
| Matertial       | PLS (handles/grips), TPU 95a (spring) |


## Results

{% include gallery caption="Final Pair of Pliers" %}


## Pliers In Action!

![Pliers in Action](/assets/img/PliersGIF.gif)


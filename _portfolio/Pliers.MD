---
title: "Multi-Material Pliers"
excerpt: "Zero-Assembly Pliers Using PLS and TPU 95a"
header:
  teaser: assets/img/Pliers.png
gallery:
  - image_path: assets/img/Pliers.png
---
---

## Project Description

This project is about designing and 3D printing needle nose pliers that can pick up and release through-hole resisitors. The multi-material “print-in-place” technique creates movable parts without extra assembly. Due to printer limitations, the handles and spring are printed separately and snapped together in this project. A flexible material acts as a spring, keeping the pliers open when not in use. Print-in-place designs are commonly used for items like wrenches, phone stands, and hinges, where connected parts need to move freely. This technique works best with a combination of materials. Flexible ones like TPU or TPE for parts that need bending, and rigid ones like PLA or ABS for structural pieces are common combinations.

<br>

## CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a42b7161957b2ffb5d?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<br>

## Design, Process, & Specifications

The key aspects of this design include the connection points, the center spring, and the clamping mechanism. 

###### Connection Points
Starting with the connection mechanism, 4 small dovetails were initially modeled on each edge of the central spring. However, the 2x5 mm size led to some minor printing inaccuracies that disturbed the smooth, snapping fit. The size of the dovetails were doubled to 4x10 mm to help fix this problem and prevent brittle pieces from breaking off. This consequently reduced the number of dovetails per edge from 4 to 2. The next step was determining the offset for the dovetail fits. Offsets of 0.2 mm, 0.05 mm, and 0 mm were all rapidly prototyped. Both models with offsets were too loose, but the zero-offset model snapped together perfectly.

###### Central Spring
The center piece was modeled as a filled-in square in Fusion360, then the spring grid lines were created in SuperSlicer. By utilizing a rectilinear infill pattern with low density, the spring could be quickly prototyped and edited. This piece was 3D printed using TPU 95a, which allowed for the flexibility of the piece when pinched on by the handles. After a few iterations, a slightly higher perimeter shell count with a rectilinear infill density of 8.5% yielded the best results.

###### Clamping Mechanism
The handles and claws were modeled out of PLS. This part allowed for the most creativity in the design, with only a few important notes to keep in mind. The area between the two handles and at the corner of the spring needed to have some clearance. Otherwise, the top of the handles would clash when attempting to pinch. Also, the relative distance between the natural position of the handles and the natural position of the claws was crucial. The handles needed to have a wider gap to ensure that the claws would clamp down all the way when squeezed. One other thing to keep in mind was the angle of conversion for the grabbing part of the claws. The goal is to have them relatively flush when attempting to pick up an object. Too steep or too shallow of angle forces the claws to converge at a single point, leaving only a small area of grabbing contact. In terms of specific dimensions, the length of the handles was 80 mm and the length of the claws was 55 mm. More importantly, the gap between the bottom of the handles was 40 mm and the gap between the pinching area of the claws was 10 mm. This 4:1 ratio was ideal for range of motion and gripping power.

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

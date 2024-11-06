---
title: "uFluidic Device"
excerpt: "Pinched Flow Fractionation - Particle Separator"
header:
  teaser: /assets/img/deviceandmold.jpg
gallery:
  - image_path: assets/img/deviceandmold.jpg
math: true
---
---
<br>

## CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a4dc2a679a11fc4179?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

<br>

## Introduction

Microfluidic (uFluidic) devices are essential in various fields due to their ability to precisely manipulate small volumes of fluids. One of the applications of these devices is in **pinched flow fractionation (PFF)**, a method used to separate particles based on their size without the need for complex filters or membranes. In PFF, particles in a fluid stream are guided through a pinched region where larger particles are displaced differently than smaller ones, allowing for effective size-based sorting in the expansion region that follows. This technique is valuable in biomedical applications, such as separating cells or particles in diagnostics and therapeutic processes, where precise and efficient sorting is critical.

However, achieving effective particle separation within such a small device presents challenges. The design of the pinched region and expansion geometry is critical to ensure that particles of different sizes are reliably separated by lateral displacement. The laminar flow characteristic of microfluidics limits mixing and turbulence, making it essential to rely on carefully engineered flow paths and geometries to achieve the desired fractionation.

<br>

## Device Rationale

This project utilizes **Pinched Flow Fractionation (PFF)** to separate particles based on size by leveraging laminar flow and specific channel geometries. The device comprises distinct regions designed to guide particle behavior and enable effective separation:

- **Inlet Region**: With a diameter of 1.65 mm and a height of 2.0 mm, the inlet introduces the buffer and sample streams. A 6:1 buffer-to-sample flow rate ratio is maintained to ensure stable, laminar flow, essential for precise particle separation. The aspect ratio of 1.21:1 supports both structural integrity and controlled flow.

- **Pinched Region**: The pinched region, measuring 1.1 mm in width, 2.0 mm in height, and 8.8 mm in length, compresses the flow, guiding particles into distinct streamlines based on size. Larger particles (0.55 mm in diameter) stay near the centerline, while smaller particles (0.165 mm) are displaced toward the edges. The aspect ratio of 1.82:1 prevents clogging, while the length-to-width ratio of 8:1 ensures adequate particle focusing.

- **Expansion Region**: After the pinched region, the channel expands to 11 mm in width, 2.0 mm in height, and 35 mm in length. This expansion allows particles to diverge spatially based on their positions in the focused streamlines. Larger particles remain near the center, while smaller particles move outward. The expansion width-to-pinch width ratio of 10:1 provides ample space for effective separation.

- **Outlet Region**: Outlets are matched to the inlet diameter (1.65 mm) and include a gentle funnel shape with angles at 18°, which helps maintain smooth flow without re-mixing the separated particles.

The separation mechanism in the pinched flow region follows this equation:

Y = (w_p - D/2) * (w_0 / w_p)

Where:
   - \( Y \): lateral position for each particle,
   - \( w_p \): width of the pinched region (1.1 mm),
   - \( D \): diameter of the particles (0.165 mm or 0.55 mm),
   - \( w_0 \): width of the expansion region (11 mm).

This equation shows how particle size influences lateral positioning, with larger particles staying closer to the center and smaller particles diverging outward.

<br>

## Flow Rate Selection

To achieve laminar flow and stable particle separation, flow rates were calculated based on the volume of the device and a ~20 second duration for a particle to flow from beginning to end.

| **Total Flow Rate (µL/s)** | **Buffer Flow Rate (µL/s)** | **Sample Flow Rate (µL/s)** |
|----------------------------|-----------------------------|-----------------------------|
| 5.7                         | 4.9                        | 0.8                         |


Maintaining a 6:1 buffer-to-sample flow ratio is essential for stable particle focusing within the pinched region, allowing precise, size-based separation.

<br>

## Assembly Instructions

To create the final device from the 3D-printed mold, follow these steps:

1. **Print and Cure Mold**:
   - Design the mold to meet the microfluidic device specifications and print it using an SLA or DLP printer, like the Form 3+/4.
   - Wash the mold in isopropyl alcohol (IPA) for 10 minutes to remove uncured resin, air-dry tilted and upside down for 30 minutes, and then perform a brief 60-second surface cure.

2. **Parylene Coating**:
   - Apply a parylene coating to prevent PDMS curing inhibition and ensure easy release of PDMS from the mold.

3. **Cast PDMS**:
   - Mix SYLGARD™ 184 silicone elastomer at a 10:1 ratio (base to curing agent), degas the mixture to remove air bubbles, and pour it into the mold.
   - Cure the PDMS at room temperature (23°C) for 24 hours or at 65°C for 4 hours. Avoid curing above 100°C to prevent mold cracking.

4. **Plasma Bond Glass Slide**:
   - After curing, demold the PDMS and inspect it for imperfections.
   - Treat both the PDMS and a glass slide with a plasma cleaner, then align and bond them to create a sealed, leak-proof microfluidic device.

<br>

## Mold and Casted Device

{% include gallery caption="" %}

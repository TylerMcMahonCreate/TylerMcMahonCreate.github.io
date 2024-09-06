---
title: "Syringe Pump"
excerpt: "Automated Syringe Pump with Variable Flow Control"
header:
  teaser: /assets/img/SyringePumpCoverPhoto.png
gallery:
  - image_path: assets/img/SyringePumpRender.png
   
---

# Purpose

A syringe pump is a specialized precision device designed to deliver fluids in a controlled manner. Some controllable factors include dispensing an exact specified volume of liquid or dispensing liquid at a set flow rate. These pumps are widely used in medical and laboratory settings due to this ability to administer exact volumes of liquid at specific rates. This is crucial in applications such as drug delivery and chemical reactions.

# Features

* On/Pause Switch: Pushing this button stops the progress of the syringe pump. Allows for immediate user control.
* Forward/Backward Jog Buttons: The jog buttons rotate the stepper motor and move the syringe back anf forth. Enables a manual mode, allowing more control over the motion of the pump. 
* The Potentiometer: Adjusts the flow rate. Enables quick changing of the pump's speed without having to edit the Arduino code.
* LED: Programmed to be green when the pump is moving, yellow when paused, and red when it is out of fluid.

# CAD Model
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a48c8428571d48595c?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

# Off-the-shelf Parts

| Off-the-shelf Parts                                                   | Quantity |
|-----------------------------------------------------------------------|----------|
| 250 mm lead screw with 2 mm pitch and 2 mm lead	                      | 1        |
| 1/4” x 8mm Flexible Coupling	                                        | 1        |
| 200 mm linear rod with 8 mm diameter                                  | 2        |
| LM8UU Linear bearing for 8 mm diameter rod                            | 2        |
| 2040 Aluminum Extrusion 1’ Length	                                    | 1        |
| Nema 17 Stepper Motor	                                                | 1        |
| MEAN WELL RQ-65D AC-DC Power Supply Quad Output 5V 12V 24V 12V 4 Amp	| 1        |
| Arduino Uno                                                         	| 1        |
| A4988 Stepper Driver                                                	| 1        |
| Small Breadboard	                                                    | 1        |
| Panel Mount Latching Push Buttons	                                    | 1        |
| Panel Mount Momentary Push Buttons                                   	| 3        |
| LCD Display	                                                          | 1        |
| Limit Switch                                                         	| 1        |
| RGB Common Cathode LED	                                              | 1        |
| Potentiometer	                                                        | 1        |

# 3D Printed Parts

| 3D Printed Parts       | Quantity |
|------------------------|----------|
| Carriage	             | 1        |
| Enclosure Top & Bottom | 1        |
| End Support            | 2        |
| Motor Mounting Plate   | 1        |

# Arduino Code

The Arduino Code used to program the Syringe Pump - [here](https://github.com/TylerMcMahonCreate/TylerMcMahonCreate.github.io/blob/main/assets/syringe-code)

{% include gallery caption="CAD Model Render" %}

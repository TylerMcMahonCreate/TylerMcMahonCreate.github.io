---
title: "Generative AI Skateboard Truck"
excerpt: "Truck for Electric Slateboard - Generative Design"
header:
  teaser: assets/img/Pliers.png
gallery:
  - image_path: assets/img/Pliers.png
---
---

## Project Description

For this project, I designed a generative truck hanger with an integrated motor mount for an electric longboard. The goal was to explore how generative design can create lightweight parts that still meet specific performance requirements. I worked within design criteria such as fitting over a standard kingpin, preserving key geometries, and accommodating components like the brushless motor
<br>
I created and analyzed designs for two materials. The Nylon 12 and ALSi10Mg designs were optimized to reduce mass while maintaining structural integrity for load cases that mimic forces such as crashing and turning. After developing CAD models, I focused on the ALSi10Mg design for powder printing, which was assessed for functionality and adherence to the project goals. The project also involved integrating generative outcomes into a complete longboard assembly and considering other potential applications of generative design throughout the process


<br>

## CAD Models - ALSi10MgCAD (left) and Nylon 12 (right)

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH286ddQT78850c0d8a42b7161957b2ffb5d?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

<br>

## Discussion

Here are my overall thoughts on this project:

###### Powder Bed Fusion and Generative Design

Powder bed fusion (PBF) and generative design work well together because they each solve different problems in manufacturing. PBF is a 3D printing process that can create detailed and complex shapes without needing molds or special tools. Generative design takes this a step further by helping engineers create lighter, more efficient parts. Together, they allow for parts that are not only strong but also save material and can combine multiple components into one.
<br>
One example of this pairing in the aerospace industry is Airbus, which redesigned a partition for its A320 planes using generative design. They were able to cut the part’s weight by 45%, which helped the plane use less fuel. The automotive industry also benefits from these technologies. General Motors, for example, used generative design to redesign a seat belt bracket. They went from eight separate parts to just one, which made manufacturing easier and reduced the part’s weight. These examples show why combining PBF and generative design is so useful, especially for industries that need lightweight and high-performing components.

###### Applying Load Cases
For this project, setting up the right load cases was important to make sure the truck hanger and motor mount design would work well in real life. I assumed a rider weight of 250 lbs to cover the higher end of average weights, so the part would be strong enough for most people. For the motor torque, I estimated the forces using common values for similar brushless DC motors. These estimates gave me a good idea of the kinds of stresses the part might face.
<br>
I placed a structural constraint at the pivot area where the truck connects to the kingpin. This was done to make sure the hanger stayed stable and wouldn’t bend or deform under stress. Every force and constraint I added was intentional. I wanted to make sure the design was strong and efficient without adding too much extra weight.
<br>
Even though I used these estimates, it’s hard to predict all the forces perfectly. Using intuition and what I know about how these parts work, I was able to get a design that should perform well. In the future, using more precise data, like measurements from sensors, could make the design even better. Knowing the exact size and direction of the forces would help refine the generative process and lead to an even stronger and lighter part.

###### Material Comparison
The two materials used in this project, Nylon 12 and ALSi10Mg, had very different results. Nylon 12 is lightweight and flexible, which comes at a cost. It’s cheaper and easier to work with, but it’s not strong enough for high-stress situations like supporting a rider’s weight. This can be seen in the model above, as the blocky shape is formed to compensate for forces that are too high. On the other hand, ALSi10Mg was much stronger and better for real-world use. However, it was heavier and more expensive than Nylon 12.
<br>
In the end, the choice of material depends on what the part will be used for. If weight and cost are the most important factors, Nylon 12 could work well for testing or low-stress applications. But for something that needs to handle a lot of force, like the truck hanger on a motorized longboard, ALSi10Mg is a better option because of its strength and durability.

###### Generative Design Critique
Generative design has a lot of advantages, like reducing the weight of parts and making shapes that are more efficient than traditional designs. It also helps combine several parts into one, which can make manufacturing faster and simpler. However, it’s not perfect. It requires a lot of computer power, and the designs often need adjustments before they can actually be made. Sometimes, the software doesn’t always give practical results if the constraints or load cases aren’t set up extremely accurately.
<br>
Even with these challenges, generative design is very useful in industries like aerospace, automotive, and medical devices. For example, medical implants can be customized to fit patients better while still being lightweight and strong. As software gets better and more affordable, I think generative design will be used in more fields. It’s a tool with a lot of potential, especially when combined with advanced manufacturing methods like powder bed fusion.


## Results

{% include gallery caption="Final Pair of Pliers" %}


## Pliers In Action!

![Pliers in Action](/assets/img/PliersGIF.gif)


---
layout: project
title: Linear actuator
description: Statics Project
technologies: [None]
image: /assets/images/actuator.png
---

Problem:
Using a linear actuator provided from a catalogue, a rod of any length, and three pins, design a structure to lift the largest possible weight to the highest possible height. The design space is two dimensions with a maximum length of 150 cm and a maximum height of 50 cm.

When treating the bar as rigid, I analyzed the system as a truss using the method of joints. The actuator and rod were connected to the ground with one pin each, and my goal was to use the maximum height. Though I could have made a perfectly vertical system, I decided that a triangle would grant more stability even if I had to trade some of its ability to support weight. The drawing for the rigid rod is as follows:

![Rigid actuator design]({{"/assets/images/actuator_rigid.jpeg" | relative_url}}){: .inline-image-r style="width: 200px"}

However, the rod is better treated as a beam that can bend under the forces of the actuator and weight. We'll assume that the tensile forces are negligible, the beam is prismatic, and that the weight of the beam itself is negligible to use bending analysis. To make sure the model is not statically indeterminate, we'll assume that the reactions at each connection to the ground is the same.

(pic)

Due to the nature of this design, bending is unlikely to be the main failure mode. Instead, buckling or tensile stress is more likely to affect it. Solving a stress balance shows that displacement=530kN*m/EA.

Using tables, it seems that Alloy5456-H1116 Aluminum will be the most mass-effective option using a circular rod of 

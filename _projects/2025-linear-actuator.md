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

Due to the nature of the weight being held at the pin at the end, the rod will not act like a bending beam. However, it is still in danger of acting like a buckling column. This will be planned with a factor of safety of 3.

![Buckling calcs]({{"/assets/images/actuator-calcs.jpeg" | relative_url}}){: .inline-image-r style="width: 200px"}
![Table]({{"/assets/images/actuator-table.jpeg" | relative_url}}){: .inline-image-r style="width: 200px"}

From the results above, the best option for the rod is an 80mm circular beam made of Alloy-5456-H116 Aluminum.

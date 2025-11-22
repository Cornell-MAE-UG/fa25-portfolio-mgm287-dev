---
layout: project
title: Heat Exchanger
description: Thermo Project
technologies: [None]
image: /assets/images/exchanger.jpg
---


A heat exchanger is a common thermodynamic device used to heat or cool a liquid. In its simplest form, two liquid streams at different temperatures run through the heat exchanger and transfer heat to each other. The cooler liquid will heat up due to the heat from the hotter liquid, and vice versa.


![Schematic of example and system diagram of heat exchanger]({{"/assets/images/exchanger-schematic.jpeg" | relative_url}}){: .inline-image-r style="width: 200px"}


In an ideal heat exchanger, the device is completely insulated with the outside world, so Q = 0. Furthermore, no work is needed to keep the liquids flowing. When the device has been working for a while, it should be approximated as steady state, so mass in = mass out. The liquids are always on the same plane as each other, so there's no change in potential energy, and kinetic energy changes will likely be negligible. From these assumptions, the following relation can be made:


![Control volume equation]({{"/assets/images/exchanger-calcs.jpeg" | relative_url}}){: .inline-image-r style="width: 200px"}


We used a heat exchanger running in parallel as a baseline. From the relation found, we would expect both parallel and counter flows to have the same ratio of delta Ts, with the change in the temperature of the cold water half of that of the hot when the hot pump is half as strong as the cold pump. However, our results don't quite match these predictions. The ratio of delta Ts for both parallel and counter flows are close to each other, but they're smaller than 1 than we predicted. With less flow, the ratio was smaller, but not as small as 0.5. We didn't know exactly what + and - on the pumps corresponded to for volumes, so our half estimate could be incorrect. Furthermore, the heat pump was heating up throughout the device, so there was heat transfer that was unaccounted for. 

![table of values]({{"/assets/images/exchanger-table.jpeg" | relative_url}}){: .inline-image style="width: 500px"}


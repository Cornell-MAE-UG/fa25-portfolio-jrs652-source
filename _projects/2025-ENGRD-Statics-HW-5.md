---
layout: project
title: Statics - HW 5
description: System Design Problem
technologies: [None]
image: /assets/images/Screenshot 2025-10-10 214629.png
---


In this problem, we were given a 2D design space of the dimensions 1.5m long and .5m tall, along with a rod of variable length, three pins, and a catalog from which to pick an actuator to design a frame/mechanism to lift the heaviest object the highest. To do this, it is important to establish that I will be considering the weight of the bar to be irrelevant, and will be setting it to zero. I set up the system as a bar pinned to the ground at one end, and pinned to a vertical IMA 22 actuator at the other (which itself is pinned to the ground). The IMA 22 can extend well beyond the 50 cm constraint given, so I set it to the max height and placed the weight being liefted directly over it, which demonstrates that this system can lift the max-rateed thrust of 1,446 Newtons provided. I previously experimented with another design that would account for potential bar weight by placing the actuator 10cm(cos(angle CAB)) closer to the center, which would, assuming the weight is greater than the bar, attempt to account slightly for the moments of both. However, I determined in a problem where we have to determine maximum possible weight, moving off the line of action decreases the maximum weight that could be accounted for, so I went with this design instead.
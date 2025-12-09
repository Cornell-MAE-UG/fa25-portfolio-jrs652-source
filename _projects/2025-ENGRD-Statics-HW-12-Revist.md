---
layout: project
title: Statics - HW 5/12 Revisit
description: System Design Problem
technologies: [None]
image: /assets/images/Screenshot 2025-10-10 214629.png
---

Problem Definition: Given a 150cm x 50 cm 2D design space, a bar of fixed length, 3 pins (two of which on the ground) and a linear actuator, make a system to life the most weight possible the highest ASSUMING RIGIDITY.

Original Static Analysis: The IMA 22 can extend well beyond the 50 cm constraint given, so I set it to the max height and placed the weight being lifted directly over it, which demonstrates that this system can lift the max-rateed thrust of 1,446 Newtons provided. I previously experimented with another design that would account for potential bar weight by placing the actuator 10cm(cos(angle CAB)) closer to the center, which would, assuming the weight is greater than the bar, attempt to account slightly for the moments of both. However, I determined in a problem where we have to determine maximum possible weight, moving off the line of action decreases the maximum weight that could be accounted for, so I went with this design instead.

Now, I intend to change this design to both continue to account for any moments that may be produced by the weight, and simplify the analysis. The bar will now be attached to the wall at 50cm up, with the position of the actuator being at x = 150cm

Finding Maximum Deflection: A moment analysis from point A, while taking the bar as the system shows that with an x-reaction in the same line of action, would find that since Rcx is in the same line of action, there is no net moment produced for a weightless bar, even if not rigid. This means that deflection would be some form of y(x) = (c1x + c2)/EI. I ran out of time studying to continue this further, unfortunately, but pinned boundary conditions would allow for the deduction of c1 and c2.
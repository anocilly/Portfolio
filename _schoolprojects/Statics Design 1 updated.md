---
layout: school_project
title: Linear Actuator Load Support
description: Theoretical Design Project
image: /assets/images/linear_actuator_design.png
---

<div class="info-box" style="border-left-color: #0077cc; background:#f2f7ff;">
  <h3 style="color: black;">Project Outline</h3>
  <p style="color: black;">For statics class, we were asked design a system using a linear actuator of our choice, a rigid bar, and three pin joints to be placed within a constrained 2D design space that could lift a load to the heighest point possible.</p>
</div>

## Design Constraints
- 2D design space 150 cm wide and 50 cm tall
- Bar of fixed length
- 3 pin supports with two needing to be mounted on the ground

## Objective
- Create a mechanism can lift the maximum possible weight to the highest possible height
- Degrees of freedom: choice of linear actuator, arrangement of components

## Initial Design:
<div class="image-container">
  <img
    src="{{ '/assets/images/linear_actuator_design.png' | relative_url }}"
    alt="Shaded rendering of earlier version"
    style="margin-bottom: 20px;">
</div>

## Initial analysis and thought process
A basic lever with the fulcrum/pivot at an end of the bar, acting as a simple lever, seemed the best way to use pins and a linear actuator to lift a weight.
Other possible designs, such as placing the linear actuator under the center of the bar and simply lifting the entire setup would not have utilized the three given pins.
When modeling the path of the lever as a quarter circle in the +x, +y quadrant, I figured placing the linear actuator at an end of the bar maximizes the torque provided by the linear actuator, maximizing the weight liftable.
Subsequent design decisions, such as the specific length of the bar, were chosen to provide the system physical leeway.

## Full Analysis:
For futher analysis, I explored how the beam would bend under loading, which can be viewed below.
Essentially, maximum bending would occur under a horizontal loading scenario with the applied weight halfway along the length of the bar.

To see my full analysis, view the file below.
Full design: [Downloadable]({{ "/assets/Linear Actuator Design.pdf" | relative_url }}) in PDF format.
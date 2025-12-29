---
layout: post
title: Actuators for robotic hand
order: 3
description:  Miniaturization of low-impedance actuators for a humanoid robotic hand. [urop @ Improbable AI, CSAIL]
skills: 
- CAD
- prototyping
- electrical design
main-image: /finger.png
---

## details
Robotics has historically relied on high impedance actuators, which require operation in structured environments and reliance on path planning. Unexpected interactions thereby lead to potential damage to the robot or its environment. This project contributes to the development of compliant actuators for a dexterous robotic hand that is safe to interact with. The low impedance (quasi-direct drive) actuators used minimize inertial and frictional losses by employing high-torque motors with low-reduction gearboxes. Reducing the gear ratio enhances backdrivability, allowing:
1. response to external forces to not be limited by motor speed and
2. force control to be achieved through current sensing.
This work was conducted under the guidance of my mentor, Branden Romero.

## role
- Miniaturizing the actuator for the distal interphalangeal (DIP) joint of the hand.
{% include image-gallery.html images="fingergears.png" height="400" %}
[Gearing of the DIP joint]
Due to the compact design, higher gear reductions are necessary to maintain similar performance. In addition to sizing, modelling, and fabricating gears to fit a small form, this required me to evaluate the drawbacks of increased mechanical impedance from increasing gear reductions. 
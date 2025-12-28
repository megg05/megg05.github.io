---
layout: post
title: "[in progress] Hybrid fixed-wing VTOL flight"
order: 1
description:  Agile flight control for an autonomous hybrid aerial vehicle. [urop @ Aerospace Controls Lab]
skills: 
- CAD
- prototyping
- electrical design
main-image: /planewiring.jpg
---

## overview
This project focuses on extending flight time of fixed-wing unmanned aerial vehicles (UAVs) by taking advantage of thermal updrafts in the environment. Planning and control algorithms are being developed to improve autonomous soaring capabilities in a controlled indoor high-bay. To test, we are setting up a hybrid fixed-wing VTOL, which requires control allocation for transitions between flight modes to accomplish agile flight. This work is conducted under the guidance of my graduate mentor, Lili Sun.

## current tasks
1. System identification of the XK40, including characterization of actuators and in-flight vehicle dynamics.
{% include image-gallery.html images="proptesting.jpg" height="400" %}
[Test bench setup for characterization of a fixed-wing propeller on the XK40.]
2. Improving simulation model fidelity for validating new controller design.
3. Formulating a control problem and implementing a control scheme on a PX4 flight computer.
4. Electrical system design (selection of components and wiring) for custom control of propellers and servos.
{% include image-gallery.html images="planewiring.jpg" height="400" %}
[Wiring in progress for integration of our flight computer.]
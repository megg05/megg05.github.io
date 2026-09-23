---
layout: post
title: "[in progress] Variable actuators for satellite ACS"
order: 1
description:  Deployable robotic actuators for high-precision attitude control of small satellites. [urop @ Robotic Exploration Lab]
skills: 
- programming
- prototyping
- hardware testing
main-image: 
---

## details
This project aims to develop deployable, variable-shape actuators to achieve low-vibration and high-precision fine pointing for a small satellite. Instead of adding disturbance from stepper motors or magnetic field dependencies, robotic actuators can use shifts in mass distribution to exploit conservation of angular momentum. The broad scope of the project encompasses the entire satellite design process and preparation for flight demonstration. 
This work is being conducted under the guidance of Dr. Patrick McKeen and Prof. Zac Manchester in the Robotic Exploration Lab @ MIT.

## current tasks
1. Creating a high-fidelity attitude model with Python + Basilisk for a spacecraft whose inertia tensor changes dynamically due to boom extension and retraction or tail deformation.
2. Developing fine-pointing control algorithms to handle time-varying inertia and couple between actuator deployment and satellite motion.
3. Modelling non-ideal environmental disturbances in LEO
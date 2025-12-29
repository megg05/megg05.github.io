---
layout: post
title: Critter
order: 2
description:  A autonomous/RC-capable robot for the 2.007 competition in spring 2025.
skills: 
- CAD
- prototyping
- manufacturing
main-image: /crittercool.jpg
---

## details
Critter was built for the 2.007 (Design and Manufacturing I) student competition in spring 2025. Through setting and modifying my  requirements throughout the design process, I opted to build a robot capable of autonomously flipping the levers on the game board for the full match. This involved fabricating a 2-motor chassis and a 4-bar linkage actuated by one servo to gain mechanical advantage. Full robot CAD:
{% include image-gallery.html images="crittercad.png" height="600" %}

### linkage design
The geometry of the 4-bar linkage was calculated by hand according to constraints of the lever box dimensions. Iterations of this geometry were validated by prototyping with cardboard links mounted onto a piece of wood. I was able to quickly vary the lengths and placements of these links to determine dimensions that would have been tedious to calculate by hand. Calculations for torque requirements and mechanical advantage achieved by the linkage are taken from my 2.007 design review:
{% include image-gallery.html images="linkage.png" height="800" %}
My chassis size was adjusted to be small enough to allow full reach by the linkage output, but large enough to overcome torque imposed by the extended linkage and keep wheels in contact with the ground.

### locking mechanism design
To reliably operate the levers, I created a locking mechanism for linkage output that would allow my robot to latch onto the levers by driving into them during the autonomous period:
{% include image-gallery.html images="locking.png" height="800" %}

While my strategy for the game was fairly simple, I focused on precise manufacturing of my chassis and linkage to maximize the time spent on the levers and the rate at which my robot operated them. In addition to the calculations shown above, I utilized my CAD model to design for a low center of mass and high moment of inertia so that my robot could be lightweight but stable. This allowed my robot to operate at higher speeds in both driving and operating the game board. In case of failure, I incorporated remote-control switching ability in the electrical design, although autonomous mode was more desirable due to its consistent rate of operation.

{% include image-gallery.html images="critter1.jpg" height="400" %}
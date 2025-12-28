---
layout: post
title: EMG-Based Prosthetic Control
order: 7
description:  Enhancing feedback for upper extremity prostheses via EMG signal interpretation. [urop @ Biomechatronics, Media Lab]
skills: 
- programming
- ML
- hardware testing
main-image: /psyonic.png
---

## overview
This project focused on improving prosthetic control of upper extremities using virtual representations of musculature instead of traditional signal pattern recognition. This was accomplished by training and optimizing a machine learning model to accurately predict limb trajectories based on a subject's electromyography (EMG) signals. My work built upon previous research done by my graduate mentor, Michael Fernandez, in the Biomechatronics Group.
The virtual model was integrated and tested with the Psyonic Ability Hand, an EMG-enabled prosthetic hand.

## role
1. Implemented new methods of converting EMG data to muscle activation signals via modelling muscle synergies.
2. Used a bilinear muscle model to model contraction with a rack-and-pinion mechanism.
3. Extended this research to a project for 2.086 (Numerical Computation for Mechanical Engineers) that predicted wrist joint kinematics using a rigid body experiencing bidirectional torque.
{% include image-gallery.html images="emgdata1.png, emgdata2.png" height="400" %}
{% include image-gallery.html images="emg.gif" height="400" %}
Click here for the full report: [Modeling Kinematics of a Wrist Joint](https://drive.google.com/file/d/1hopLS2eXywugHFNm3NdAk3GqWcVGg6uA/view?usp=sharing)
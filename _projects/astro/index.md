---
layout: post
title: "Low-thrust trajectory optimization"
order: 2
description:  A study of several trajectory optimization methods for a low-thrust Earth-Mars transfer.
skills: 
- programming
main-image: /psyche_image.jpg
---

## details

This research constituted a final project for graduate course 16.346 Astrodynamics in collaboration with Jing Cao and Annika Vaidyanathan. Please see the [project report](https://github.com/megg05/lowthrust-earthmars/blob/69fb8d8ff1eaa71a61d21c5d5fb81efb94796333/16_346_Final_Project.pdf) and [simulation codebase](https://github.com/megg05/lowthrust-earthmars).

(from [project report](https://github.com/megg05/lowthrust-earthmars/blob/69fb8d8ff1eaa71a61d21c5d5fb81efb94796333/16_346_Final_Project.pdf))
The first primary objective of this research is to quantify the performance advantages of SEP over traditional chemical propulsion for an Earth-Mars transfer. By using the Psyche spacecraft’s specifications as a baseline, this study evaluates the reduction in propellant mass and the specific Δv requirements for a low-thrust trajectory. Additionally, the project assesses the sensitivity of the optimized path to variables such as available thrust levels, specific impulse, and planetary launch windows to determine how these factors influence mission feasibility.

The scope of this project involves the implementation of several key modeling and optimization components. Initial work focuses on establishing a baseline through the calculation of an impulsive Hohmann transfer, including the necessary plane change to match Martian inclination. For the low-thrust analysis, we aimed to use a direct method to find a highly optimal solution, which required us to provide an initial seed trajectory. As a result, we chose to implement a Q-law controller for closed-loop initial trajectory generation and HermiteSimpson collocation for direct transcription optimization. Hermite-Simpson was chosen as a medium-order method since higher-order optimization techniques were not necessary for the scope of this project. Performance is measured using four primary metrics: total Δv, final propellant mass fraction, time of flight, and the convergence efficiency of the optimization algorithms.

The second primary objective of this paper is to evaluate aerobraking trajectories following the SEP transfer. This section of the paper has three main objectives: (1) to calculate and optimize a nominal aerobraking trajectory for a spacecraft entering Martian orbit, (2) conduct a parametric study exploring how effective aerobraking is at Mars for different spacecraft configurations, and (3) calculate metrics for trajectory selection (fuel consumption, transfer time, number of passes) to compare the effectiveness of an aerobraking trajectory to a fully propulsive insertion trajectory.
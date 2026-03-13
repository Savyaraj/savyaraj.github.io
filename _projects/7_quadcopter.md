---
layout: page
title: Trajectory Planning for 2D Quadcopter
description: Motion planning and control algorithms for quadcopter trajectory tracking in cluttered environments
img: assets/img/quadcopter_trajectory.png
importance: 7
category: past projects
---

*Undergraduate Thesis, IIT Bombay*

Developed motion planning and control algorithms for a 2D quadcopter navigating cluttered environments. Formulated optimal trajectory generation as a graph search problem by discretizing the dynamics using motion primitives ([Brescianini and D'Andrea, 2018](https://ieeexplore.ieee.org/document/8336503)) and solving with the A* algorithm.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/quadcopter_trajectory.png" title="Trajectory planning" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Benchmarked velocity-controlled trajectories (trapezoidal profiles -- easy to compute but significantly deform the optimal path) against jerk-controlled trajectories (smoother but computationally expensive in higher-dimensional search spaces). Applied [trajectory refinement](https://ieeexplore.ieee.org/abstract/document/8264768) techniques that use sub-optimal lower-dimensional trajectories as heuristics, achieving efficient planning in the full state space.

Implemented cascade PID controller architectures for trajectory tracking. Demonstrated that nonlinear controllers significantly outperform linearized approaches during dynamically demanding maneuvers.

**Report:** [PDF](/assets/pdf/report_BTP.pdf)

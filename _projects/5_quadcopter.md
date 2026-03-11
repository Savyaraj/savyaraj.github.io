---
layout: page
title: Trajectory Planning for 2D Quadcopter
description: Motion planning and control algorithms for quadcopter trajectory tracking in cluttered environments
img: assets/img/quadcopter_trajectory.png
importance: 5
category: past projects
---

Developed motion planning algorithms for a 2D quadcopter navigating cluttered environments and implemented control algorithms for precise trajectory tracking. Used motion primitives-based trajectory discretization (Brescianini & D'Andrea, 2018), converting the optimal control problem into a graph search problem solved via the A* algorithm.

Compared velocity-controlled (trapezoidal) and jerk-controlled trajectories, implementing trajectory refinement techniques for computational efficiency in higher-dimensional search spaces. Cascade PID controller architectures were designed for trajectory following, with nonlinear controllers demonstrating superior performance over linearized approaches.

**Institution:** IIT Bombay (Undergraduate Thesis)

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/quadcopter_trajectory.png" title="Trajectory planning" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

**Report:** [PDF](/assets/pdf/report_BTP.pdf)

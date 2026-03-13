---
layout: page
title: Neural Controllers for Locomotion
description: Design and analysis of CPG-based neural controllers for animal and robot locomotion
img: assets/img/cpg_locomotion.png
importance: 5
category: past projects
related_publications: false
---

*Semester Project, [Biorobotics Laboratory (EPFL)](https://www.epfl.ch/labs/biorob/)*

Designed and simulated biologically inspired neural controllers for animal and robot locomotion using Central Pattern Generators (CPGs) -- dynamical systems that produce stable oscillatory behavior without phasic input ([Ijspeert, 2008](https://www.sciencedirect.com/science/article/abs/pii/S0893608008000804)). Applied the Neural Engineering Framework ([Eliasmith and Anderson, 2004](https://mitpress.mit.edu/books/neural-engineering)) to construct CPGs from neuron populations with analytically derived network weights and guaranteed stability -- replacing black-box optimization with principled, interpretable formulations.

The following video gives a glimpse of the lamprey swimming using the framework:

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <video width="100%" controls poster="/assets/video/robot_swimming_poster.png">
            <source src="/assets/video/robot_swimming.mp4" type="video/mp4">
        </video>
    </div>
</div>

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cpg_locomotion.png" title="CPG schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Integrated the controllers into the [FARMS](https://gitlab.com/farmsim) (Framework for Animals and Robots Modelling and Simulation) platform and validated them on lamprey swimming simulations.

Performed nonlinear dynamical analysis of locomotion controllers using numerical continuation ([Allgower and Georg, 2003](https://epubs.siam.org/doi/book/10.1137/1.9780898719154)) to compute equilibria, limit cycles, and bifurcation points. Leveraged the Coco continuation toolbox ([Dankowicz and Schilder, 2013](https://epubs.siam.org/doi/book/10.1137/1.9781611972573)) to map out dynamical regimes and characterize the stability landscape of rhythm generation mechanisms.

**Report:** [PDF](/assets/pdf/report_biorob.pdf)

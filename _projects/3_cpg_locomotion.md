---
layout: page
title: Neural Controllers for Locomotion
description: Design and analysis of CPG-based neural controllers for animal and robot locomotion
img: assets/img/cpg_locomotion.png
importance: 3
category: past projects
related_publications: false
---

Developed and simulated control mechanisms for locomotion in animals and robots using biological models of neural networks based on Central Pattern Generators (CPGs). CPGs are dynamical systems that produce stable oscillatory behavior and serve as the underlying mechanism for rhythmic motor patterns observed in nature.

The project employed the Neural Engineering Framework (Eliasmith & Anderson) to develop CPGs using a population of neurons with analytical network weight formulations. The resulting neural controllers were tested on the FARMS (Framework for Animals and Robots Modelling and Simulation) platform for lamprey swimming simulation.

Numerical continuation methods and bifurcation analysis were used to study the dynamical regimes and stability of the CPG oscillators, leveraging the Coco continuation toolbox to characterize limit cycles and their bifurcation points.

**Institution:** Biorobotics Laboratory, EPFL (Semester Project)

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/cpg_locomotion.png" title="CPG schematic" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

{% if site.data.repositories %}
{% endif %}

**Report:** [PDF](/assets/pdf/report_biorob.pdf)

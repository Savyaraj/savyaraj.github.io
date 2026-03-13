---
layout: page
title: Diversity Induced Resonance
description: Optimal noise and parameter diversity inducing coherent periodic responses in coupled nonlinear oscillators
img: assets/img/diversity_resonance.png
importance: 8
category: past projects
---

*Nonlinear Dynamics Laboratory Course Project, IIT Bombay*

Investigated a counterintuitive phenomenon in coupled nonlinear oscillators: [diversity induced resonance](https://arxiv.org/abs/0808.0522), where an optimal amount of parameter noise induces maximally coherent behavior rather than disorder. Studied this using coupled [logistic maps](https://en.wikipedia.org/wiki/Logistic_map) -- the discrete analog of population dynamics -- focusing on the period-5 window in the bifurcation diagram.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/diversity_resonance.png" title="Bifurcation diagram" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Coupled the oscillators via a global mean field term and demonstrated that in the chaotic region at the edge of the period-5 window, optimal parameter noise pushes the system into period-5 dynamics. The phenomenon proved robust across system sizes and coupling strengths. Developed a reduced mean field model that accurately replicated the shifts in periodic windows, enabling analytical tractability.

Extended the analysis beyond the mathematically convenient global coupling to non-local coupling -- a more physically realistic model of coupled dynamics -- and confirmed coherent behaviors persist even for smaller interaction ranges.

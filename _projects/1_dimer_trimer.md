---
layout: page
title: Soliton Hopping in Coupled Microresonators
description: Exact periodic orbit solutions and bifurcation structure underlying soliton hopping in coupled optical microresonators
img: assets/img/dimer_trimer_soliton.png
importance: 2
category: research
---

Computed **exact periodic orbit solutions** of coupled Lugiato-Lefever equations that underlie soliton hopping -- a dynamic process where solitons periodically transit between coupled optical microresonators. Mapped full solution branches in parameter space using **Newton-Krylov continuation methods** and **bifurcation analysis**.

<div class="row justify-content-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dimer_trimer_soliton.png" title="Soliton hopping in coupled microresonators" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

Revealed a fundamental difference between dimer and trimer configurations: soliton hopping originates from a **subcritical Hopf bifurcation** in dimers but a **supercritical Hopf bifurcation** in trimers. This distinction has practical consequences -- trimers require an **order-of-magnitude lower pump power** (~25 mW vs ~230 mW), making them significantly more accessible for experimental realization of soliton-based frequency comb technologies.

Characterized the full existence regions for soliton hopping in detuning--pump power parameter space, identifying saddle-node bifurcations that define the boundaries of hopping regimes and explaining rate-dependent hysteresis observed in laser scan experiments.

Built on a **C++/Python** simulation stack with **spectral discretization** and **Krylov-subspace** linear solvers. Code available at [channelflow-dedalus](https://github.com/Savyaraj/channelflow-dedalus).

**Publication:** [Commun. Phys. (2026)](https://www.nature.com/articles/s42005-026-02623-6) — [arXiv:2508.09921](https://arxiv.org/abs/2508.09921)

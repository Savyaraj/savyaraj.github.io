---
layout: page
title: Soliton Self-Injection Locking in Microresonators
description: Bifurcation structure and deterministic access to single-soliton states in self-injection-locked microcombs
img: assets/img/sil_bifurcation.png
importance: 1
category: research
---

Developed a **bifurcation-theoretic description of soliton self-injection locking (SIL)**, where light backscattered from a high-quality-factor microresonator provides frequency-selective feedback to a semiconductor laser. This compact configuration can strongly narrow the laser linewidth while directly supporting dissipative Kerr solitons (DKSs), the ultrashort pulses underlying coherent chip-scale frequency combs.

<div class="row justify-content-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/sil_bifurcation.png" title="Self-injection-locking setup, soliton bifurcation branches, and representative intracavity profiles" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">A diode laser receives phase-sensitive feedback from the microresonator (left). Self-injection locking reshapes the one-, two-, and three-soliton solution branches (top right), whose representative intracavity profiles are shown below.</div>

Modelled the system using coupled **Lugiato--Lefever and diode-laser equations** in the experimentally relevant weak-backscattering limit. Applied **Newton--Krylov continuation methods** to compute stationary soliton branches, determine their stability, and follow them across the experimentally controlled free-laser detuning and feedback phase.

Showed that phase-sensitive feedback slants the conventional ladder of DKS branches, creating **soliton-number-dependent existence ranges**. This restructuring produces parameter regions in which the single-soliton state exists without competing multi-soliton states, providing a principled route to deterministic state selection through the feedback phase and microresonator design.

Confirmed that these stationary bifurcation structures govern experimentally relevant dynamics. Direct time-domain simulations with prescribed detuning and phase sweeps move the system down the multi-soliton ladder and into a stable **single-soliton attractor**, establishing a practical strategy for reliable, low-noise microcomb generation.

**Publication:** [Optics Letters 51, 4817--4820 (2026)](https://doi.org/10.1364/OL.608452) — [arXiv:2606.29921](https://arxiv.org/abs/2606.29921)

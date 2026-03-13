---
layout: page
title: Computational Modelling of Spinal Neural Circuits
description: Neural network models explaining frequency-dependent muscle recruitment during epidural electrical stimulation
img: assets/img/neurorestore_network.png
importance: 4
category: past projects
---

*[NeuroRestore](https://www.neurorestore.swiss/), Lausanne University Hospital / EPFL*

Built **computational neural network models** in the **NEURON** simulation framework to explain asymmetric recruitment of flexor vs extensor muscles during **epidural electrical stimulation (EES)** -- a promising neurotechnology for motor restoration after spinal cord injury.

<div class="row justify-content-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/neurorestore_network.png" title="Baseline spinal sensorimotor network" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">Baseline spinal sensorimotor network with Group I/II afferent pathways and reciprocal inhibition.</div>

Developed and tested multiple mechanistic hypotheses for frequency-dependent effects: **flexor reflex afferent (FRA)** pathways through dorsal horn interneurons, **wide dynamic range (WDR) neuron** windup dynamics with upregulated calcium currents post-injury, and **short-term synaptic plasticity** mechanisms tied to muscle fiber types (facilitating synapses for fast-twitch flexor motoneurons, depressing synapses for slow-twitch extensors). Extended plasticity models with fast and slow **calcium buffer kinetics** to capture multi-scale temporal dynamics observed experimentally.

Performed **parametric sensitivity analysis** across model parameters and validated simulations against experimental EMG recordings from rat models:

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/neurorestore_RF_sim.png" title="EMG simulations — extensor (RF)" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/neurorestore_RF_data.png" title="EMG experimental data — extensor (RF)" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">Comparison of EMG simulations and experiments — extensor (RF).</div>

<div class="row justify-content-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/neurorestore_TA_sim.png" title="EMG simulations — flexor (TA)" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/neurorestore_TA_data.png" title="EMG experimental data — flexor (TA)" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">Comparison of EMG simulations and experiments — flexor (TA).</div>

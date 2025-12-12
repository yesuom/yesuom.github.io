---
title: "LIF Neuron Model"
date: 2025-12-12
draft: false
tags: ["Neuroscience", "SNN"]
---

Here is a note about **Leaky Integrate-and-Fire (LIF)** model.

## The Equation

The dynamics of the membrane potential $V(t)$ is described by:

$$
\tau_m \frac{dV}{dt} = -(V(t) - V_{rest}) + R \cdot I(t)
$$

Where:
* $\tau_m$ is the membrane time constant.
* $I(t)$ is the input current.

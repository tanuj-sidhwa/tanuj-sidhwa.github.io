---
layout: single
title: "Numerical Methods for a Micro Cold-Gas Thruster"
author_profile: false
permalink: /projects/micro-thruster/
description: "Finite-volume compressible-flow modelling with HLLC and MUSCL–HLLC for nozzle flow and shock resolution."
---

<p class="research-meta">AA374 Computational Fluids and Structures · IIT Indore · January–April 2026</p>

<p class="research-detail__lede">Developed a quasi-one-dimensional finite-volume model of compressible flow through a converging–diverging nozzle, with emphasis on accuracy and numerical stability when resolving shocks and strong flow gradients.</p>

<figure class="project-figure">
  <img src="{{ '/assets/images/cfs.png' | relative_url }}" alt="Numerical nozzle flow result from the cold-gas thruster project" loading="lazy">
  <figcaption>Selected numerical visualization from the cold-gas thruster project. Additional comparison plots can be added with flow conditions and axes described explicitly.</figcaption>
</figure>

## Governing problem and numerical methods

- Modelled compressible flow using quasi-one-dimensional Euler equations.
- Implemented and compared Lax–Friedrichs, HLLC, and higher-order MUSCL–HLLC numerical formulations with slope limiting.
- Studied transonic acceleration and the effect of discontinuities on numerical predictions.
- Compared computed trends with relevant analytical nozzle-flow relations and Fluent simulations.

## Main contribution

The focus was not just generating a nozzle solution, but understanding the practical trade-off between numerical diffusion, shock resolution, and stability across different numerical schemes.

## Repository

[View the solver on GitHub](https://github.com/tanuj-sidhwa/HLLC_shock_capturing_OneDColdThruster).

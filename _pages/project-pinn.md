---
layout: single
title: "Physics-Informed Neural Networks for Engine Thermodynamics"
author_profile: false
permalink: /projects/engine-pinn/
description: "Research using Fourier-feature physics-informed models and thermodynamic constraints for diesel-engine pressure prediction."
---

<p class="research-meta">IIT Indore · Spray and Combustion Laboratory · Supervisor: Prof. Devendra Deshmukh · 2026–present</p>

<p class="research-detail__lede">This project explores whether combustion-relevant physical constraints can improve data-driven prediction of in-cylinder pressure as a function of crank angle and engine operating conditions.</p>

## Problem

Accurate engine pressure prediction requires models to capture sharp changes associated with combustion and fuel injection. Physics-informed methods offer the possibility of combining observed engine data with thermodynamic relationships, but stable training and generalization remain difficult.

## Methodology

- Used diesel-combustion data from the Sandia Engine Combustion Network for supervised and physics-informed model development.
- Explored Fourier-feature architectures to represent pressure variation over crank angle.
- Formulated physics-informed training terms using engine thermodynamics and associated operating information.
- Investigated training stability, loss balance, and predictions under held-out conditions.

## Findings and limitations

Initial modelling reproduced aspects of observed pressure traces under training conditions. However, generalization to unseen operating or injection profiles has been challenging. Accordingly, this page does not quote a single overall accuracy figure until evaluation conditions and error definitions can be stated unambiguously.

## Ongoing work

Current investigations include alternative thermodynamic parameterizations and representations of heat release, together with more rigorous out-of-sample comparisons.

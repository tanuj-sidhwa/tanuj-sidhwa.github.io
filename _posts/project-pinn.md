---
layout: single
title: "Physics-Informed Neural Network for Engine Thermodynamics"
author_profile: true
permalink: /projects/engine-pinn/
---

**Supervisor:** Prof. Devendra Deshmukh, Department of Mechanical Engineering  
**Timeline:** Jan. 2026 - Present  
**Code/Repository:** *(Repository currently private or pending)* *(Optional: Add your thumbnail image here using `![PINN Architecture](/assets/images/your-image.jpg)`)*

### Project Overview
* Developed a Pointwise Fourier Physics-Informed Neural Network (PINN) using PyTorch to predict instantaneous in-cylinder pressure, leveraging high-fidelity diesel combustion data from the Sandia Engine Combustion Network (ECN).
* Engineered a custom loss function embedding the First Law of Thermodynamics, replacing static assumptions with a dynamic specific heat ratio mapped to bulk gas temperature and experimental fuel injection rates.

### Outcomes & Results
* Resolved severe gradient conflicts and high-frequency numerical dispersion (Fourier leakage) by applying L1 Total Variation regularization, successfully reducing relative inference error on unseen injection profiles to under **7%**.

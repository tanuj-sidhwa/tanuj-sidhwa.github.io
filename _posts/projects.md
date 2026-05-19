---
layout: single
title: "Research & Projects"
author_profile: true
permalink: /projects/
---

<style>
  .project-card {
    background: rgba(255,255,255,0.05);
    border: 1px solid rgba(255,255,255,0.1);
    padding: 20px;
    border-radius: 8px;
    text-decoration: none !important;
    color: inherit !important;
    display: block;
    transition: transform 0.2s ease, border-color 0.2s ease;
  }
  .project-card:hover {
    transform: translateY(-5px); /* Makes the card float up slightly when hovered */
    border-color: rgba(255,255,255,0.4);
  }
  .project-card h3 {
    margin-top: 0;
    font-size: 1.2em;
    line-height: 1.3;
  }
  .project-card .meta {
    font-size: 0.85em;
    font-style: italic;
    opacity: 0.8;
    margin-bottom: 10px;
  }
  .project-card .summary {
    font-size: 0.9em;
    line-height: 1.5;
  }
  .project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    margin-top: 30px;
  }
</style>

<p>Select a project below to view the technical details, methodologies, and outcomes.</p>

<div class="project-grid">

  <a href="/projects/air-quality/" class="project-card">
    <h3>Assessment of Indoor Air Quality in Student Hostel</h3>
    <div class="meta">Prof. Ritunesh Kumar | Sept. 2024 - Oct. 2025</div>
    <div class="summary">Arduino-based CO2 and environmental monitoring system for residential spaces, resulting in a first-author conference paper.</div>
  </a>

  <a href="/projects/stol-wing/" class="project-card">
    <h3>Powered Lift Wing Design for STOL Applications</h3>
    <div class="meta">InterIIT Tech Meet 14.0 | Oct. 2025 - Dec. 2025</div>
    <div class="summary">Multidisciplinary design and CFD validation of a high-lift STOL wing achieving a Lift Coefficient of 6.81.</div>
  </a>

  <a href="/projects/engine-pinn/" class="project-card">
    <h3>Physics-Informed Neural Network for Engine Thermodynamics</h3>
    <div class="meta">Prof. Devendra Deshmukh | Jan. 2026 - Present</div>
    <div class="summary">Developed a Pointwise Fourier PINN using PyTorch to predict instantaneous in-cylinder pressure from diesel combustion data.</div>
  </a>

  <a href="/projects/micro-thruster/" class="project-card">
    <h3>Numerical Design of a Micro Cold-Gas Thruster</h3>
    <div class="meta">Computational Fluids and Structures | Jan. 2026 - Apr. 2026</div>
    <div class="summary">Quasi-one-dimensional finite volume solver for compressible Euler equations to model transonic and supersonic flow.</div>
  </a>

  <a href="/projects/cubesat/" class="project-card">
    <h3>CubeSat Structural Development</h3>
    <div class="meta">CAE Club & Astronomy Club | Oct. 2024 - Nov. 2024</div>
    <div class="summary">Led cross-domain team and executed detailed modal, thermal, and structural analysis of the primary chassis using ANSYS.</div>
  </a>

</div>

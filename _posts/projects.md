---
layout: single
title: "Research & Projects"
author_profile: true
permalink: /projects/
---

<p>Select a project below to expand and view the technical details, methodologies, and outcomes.</p>

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-top: 30px;">

  <details style="background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 8px; cursor: pointer;">
    <summary style="font-size: 1.1em; font-weight: 700; outline: none;">
      Assessment of Indoor Air Quality in Student Hostel
    </summary>
    <div style="margin-top: 15px; font-size: 0.9em; line-height: 1.6;">
      <p><em>Prof. Ritunesh Kumar | Sept. 2024 - Oct. 2025</em><br>
      <a href="https://github.com/varshaa886/Smart-Environmental-Monitoring-Ventilation-System" target="_blank">View on GitHub</a></p>
      <ul>
        <li>Developed an integrated Arduino-based monitoring system combining NDIR (MH-Z19B) and DHT11 sensors to collect continuous CO<sub>2</sub> concentration and environmental data for indoor air quality assessment in residential spaces.</li>
        <li>Conducted controlled experiments under varying occupancy levels to monitor CO<sub>2</sub> buildup across different ventilation conditions, capturing time-dependent concentration trends inside student hostel rooms.</li>
        <li>First author of a paper based on the project, accepted at International Conference on Thermofluids Engineering (INCOTHERM) 2025, IIT(ISM) Dhanbad, Oct. 2025.</li>
      </ul>
    </div>
  </details>

  <details style="background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 8px; cursor: pointer;">
    <summary style="font-size: 1.1em; font-weight: 700; outline: none;">
      Powered Lift Wing Design for STOL Applications
    </summary>
    <div style="margin-top: 15px; font-size: 0.9em; line-height: 1.6;">
      <p><em>InterIIT Tech Meet 14.0: High Prep – LAT Aerospace | Oct. 2025 - Dec. 2025</em></p>
      <ul>
        <li>Led a multidisciplinary team to design a high-lift STOL wing, coordinating aerodynamics, propulsion, and stability efforts while managing timelines, task delegation, and system-level integration across workstreams.</li>
        <li>Drove key technical decisions including airfoil selection, high-lift device configuration, and powered-lift concepts through trade-off studies balancing lift augmentation, drag penalties, stability margins, and computational cost.</li>
        <li>Supervised and reviewed CFD-driven design iterations in ANSYS Fluent and Workbench, ensuring consistency between 2D, semi-2D, and 3D analyses, and alignment with analytical models.</li>
        <li>Guided development and validation of multi-fidelity aerodynamic models, integrating theoretical predictions, automated CFD workflows, and parametric studies to achieve a Lift Coefficient of 6.81.</li>
        <li>Consolidated technical findings into a comprehensive end-evaluation report, synthesizing analytical modeling, numerical simulations, and performance insights for competition review and future design scalability.</li>
      </ul>
    </div>
  </details>

  <details style="background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 8px; cursor: pointer;">
    <summary style="font-size: 1.1em; font-weight: 700; outline: none;">
      Physics-Informed Neural Network for Engine Thermodynamics
    </summary>
    <div style="margin-top: 15px; font-size: 0.9em; line-height: 1.6;">
      <p><em>Prof. Devendra Deshmukh | Jan. 2026 - Present</em></p>
      <ul>
        <li>Developed a Pointwise Fourier Physics-Informed Neural Network (PINN) using PyTorch to predict instantaneous in-cylinder pressure, leveraging high-fidelity diesel combustion data from the Sandia Engine Combustion Network (ECN).</li>
        <li>Engineered a custom loss function embedding the First Law of Thermodynamics, replacing static assumptions with a dynamic specific heat ratio mapped to bulk gas temperature and experimental fuel injection rates.</li>
        <li>Resolved severe gradient conflicts and high-frequency numerical dispersion (Fourier leakage) by applying L1 Total Variation regularization, successfully reducing relative inference error on unseen injection profiles to under 7%.</li>
      </ul>
    </div>
  </details>

  <details style="background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 8px; cursor: pointer;">
    <summary style="font-size: 1.1em; font-weight: 700; outline: none;">
      Numerical Design of a Micro Cold-Gas Thruster
    </summary>
    <div style="margin-top: 15px; font-size: 0.9em; line-height: 1.6;">
      <p><em>Computational Fluids and Structures (AA374) | Jan. 2026 - Apr. 2026</em><br>
      <a href="https://github.com/tanuj-sidhwa/HLLC_shock_capturing_OneDColdThruster" target="_blank">View on GitHub</a></p>
      <ul>
        <li>Developed a quasi-one-dimensional finite volume solver for compressible Euler equations to model flow through converging–diverging nozzles, capturing transonic acceleration, shock formation, and supersonic expansion.</li>
        <li>Implemented and compared Lax–Friedrichs, HLLC, and second-order MUSCL–HLLC schemes with TVD limiters, achieving accurate shock resolution while maintaining numerical stability and computational efficiency.</li>
        <li>Validated results against analytical isentropic relations and ANSYS Fluent simulations and conducted parametric analysis to evaluate thrust and specific impulse trade-offs for micro-thruster design.</li>
      </ul>
    </div>
  </details>

  <details style="background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); padding: 20px; border-radius: 8px; cursor: pointer;">
    <summary style="font-size: 1.1em; font-weight: 700; outline: none;">
      CubeSat Project
    </summary>
    <div style="margin-top: 15px; font-size: 0.9em; line-height: 1.6;">
      <p><em>CAE Club & Astronomy Club, IIT Indore | Oct. 2024 - Nov. 2024</em><br>
      <a href="https://github.com/Vedansh7-7/CubeSat/tree/main" target="_blank">View on GitHub</a></p>
      <ul>
        <li>Led the team on the project, overseeing work distribution, workflow coordination, and cross-domain communication for smooth and coherent project progress; also handled official documentation like proposal and report drafting.</li>
        <li>Designed the Primary Chassis of the CubeSat model and conducted detailed modal, thermal, and structural analysis to ensure and validate mechanical integrity, thermal resilience, and stability under expected operational stresses.</li>
        <li>Executed precise load calculations and verified compliance with aerospace design standards, ensuring the structure could withstand launch conditions and maintain functionality throughout orbital deployment and mission lifespan.</li>
      </ul>
    </div>
  </details>

</div>
**Powered Lift Wing Design for STOL Applications**
*Oct. 2025 – Dec. 2025*
* Led a multidisciplinary team for InterIIT Tech Meet 14.0 to design a high-lift STOL wing.
* Supervised CFD-driven design iterations in ANSYS Fluent and guided multi-fidelity aerodynamic models to achieve a Lift Coefficient of 6.81.

**Assessment of Indoor Air Quality in Student Hostel**
*Sept. 2024 – Oct. 2025*
* Developed an integrated Arduino-based monitoring system using NDIR and DHT11 sensors to collect continuous CO2 and environmental data.
* Conducted controlled experiments to capture time-dependent concentration trends inside student hostel rooms.

**CubeSat Structural Development**
*June 2024 – Nov. 2024*
* Served as Project Lead and Team Lead for CubeSat initiatives, including the IITI SOC'24 Quasar 1.0.
* Designed the primary chassis and conducted detailed modal, thermal, and structural analysis using ANSYS to validate mechanical integrity under expected orbital stresses.

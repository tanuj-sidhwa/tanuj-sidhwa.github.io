---
layout: single
permalink: /
title: ""
description: "Research portfolio of Tanuj Sidhwa, IIT Indore. Computational fluid dynamics, propulsion, combustion, and scientific machine learning."
author_profile: false
---

<section class="portfolio-home">
  <div class="portfolio-hero">
    <div class="portfolio-hero__copy">
      <p class="eyebrow">UNDERGRADUATE RESEARCHER · IIT INDORE</p>
      <h1>Tanuj Sidhwa</h1>
      <h2>Computational fluid dynamics, propulsion & multiphysics research.</h2>
      <p class="hero-lead">I am a final-year B.Tech. Mechanical Engineering student at IIT Indore, exploring fluid mechanics through computational modelling, experiments, and physics-informed methods.</p>
      <p class="hero-support">My work includes electrohydrodynamic electrosprays at ISRO–LPSC, gelled-fuel droplet combustion, diesel-engine modelling, and free-surface CFD.</p>
      <div class="hero-actions">
        <a class="button-primary" href="{{ '/research/' | relative_url }}">Explore research <span aria-hidden="true">→</span></a>
        <a class="button-secondary" href="{{ '/assets/CV%20-%20Tanuj%20Sidhwa.pdf' | relative_url }}">View CV <span aria-hidden="true">↗</span></a>
      </div>
      <div class="hero-links">
        <a href="mailto:{{ site.email }}">Email</a>
        <a href="https://github.com/tanuj-sidhwa">GitHub</a>
        <a href="https://www.linkedin.com/in/tanuj-sidhwa/">LinkedIn</a>
      </div>
    </div>
    <div class="portfolio-hero__portrait">
      <img src="{{ '/assets/images/dp.jpg' | relative_url }}" alt="Portrait of Tanuj Sidhwa" width="450" height="500" fetchpriority="high">
      <div class="portrait-caption"><span class="caption-dot"></span> Mechanical Engineering · Class of 2027</div>
    </div>
  </div>

  <div class="section-heading">
    <div>
      <p class="eyebrow">CURRENT & RECENT WORK</p>
      <h2>Featured research</h2>
    </div>
    <a class="section-more" href="{{ '/research/' | relative_url }}">All research →</a>
  </div>
  <div class="research-grid">
    {% for project in site.data.research limit:3 %}
      {% include research-card.html item=project %}
    {% endfor %}
  </div>

  <div class="section-heading">
    <div>
      <p class="eyebrow">SELECTED HIGHLIGHTS</p>
      <h2>Background & recognition</h2>
    </div>
    <a class="section-more" href="{{ '/about/' | relative_url }}">About me →</a>
  </div>
  <div class="highlight-grid">
    <div class="highlight"><strong>ISRO–LPSC</strong><span>Research internship · 2026</span></div>
    <div class="highlight"><strong>GATE AE · AIR 144</strong><span>National-level examination · 2026</span></div>
    <div class="highlight"><strong>Reliance Scholar</strong><span>Undergraduate scholarship · 2024</span></div>
  </div>

  <div class="contact-strip">
    <div>
      <p class="eyebrow">GET IN TOUCH</p>
      <h2>Interested in collaborating or discussing research?</h2>
      <p>I welcome conversations about CFD, propulsion, combustion, and multiphysics research.</p>
    </div>
    <a class="button-primary" href="mailto:{{ site.email }}">Email me <span aria-hidden="true">↗</span></a>
  </div>
</section>

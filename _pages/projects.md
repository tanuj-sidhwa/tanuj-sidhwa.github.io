---
layout: single
title: "Engineering Projects"
author_profile: false
permalink: /projects/
description: "Selected projects in compressible-flow simulation, aerodynamic design, structural analysis, and experimental sensing."
---

<p class="page-intro">Selected engineering projects demonstrating numerical methods, modelling, experiment design, and multidisciplinary team work. For ongoing and recent academic investigations, visit the <a href="{{ '/research/' | relative_url }}">Research page</a>.</p>

<div class="project-grid">
  {% for project in site.data.projects %}
    {% include project-card.html item=project %}
  {% endfor %}
</div>

---
layout: single
permalink: /research/
title: "Research"
description: "Research in electrohydrodynamics, droplet combustion, diesel-engine modelling, and liquid sloshing."
author_profile: false
---

<p class="page-intro">My research interests centre on how fluid-mechanical systems can be understood using a combination of physics-based models, numerical simulation, experiments, and scientific machine learning. The projects below include completed internship work and ongoing research.</p>

<div class="research-grid research-grid--page">
  {% for project in site.data.research %}
    {% include research-card.html item=project %}
  {% endfor %}
</div>

## Research interests

**Computational fluid dynamics · Multiphase flows · Combustion and propulsion · Electrohydrodynamics · Physics-informed machine learning**

For technical details and publications, see the project summaries and my [academic CV]({{ '/assets/CV%20-%20Tanuj%20Sidhwa.pdf' | relative_url }}).

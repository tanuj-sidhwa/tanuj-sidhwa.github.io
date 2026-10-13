---
layout: single
permalink: /research/
title: "Research"
description: "Research in fluid mechanics, combustion, propulsion and computational modelling."
author_profile: true
author: tanuj
---

## Areas of interest

Computational fluid dynamics, multiphase flow, combustion, propulsion, electrohydrodynamics and scientific machine learning.

## Selected work

<div class="research-index">
  {% for project in site.data.research %}
    {% include research-card.html item=project %}
  {% endfor %}
</div>

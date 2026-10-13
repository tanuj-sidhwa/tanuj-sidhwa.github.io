---
layout: single
permalink: /research/
title: "Research"
description: "Research in fluid mechanics, combustion, propulsion and computational modelling."
author_profile: true
author: tanuj
---


## Research interests

Computational fluid dynamics, multiphase flow, combustion, aerospace propulsion, electrohydrodynamics and scientific machine learning.

<p class="section-introduction">The work below includes research carried out during internships and projects that are still in progress. Each page describes the question I am investigating, the methods I have used and the present state of the work.</p>

## Research work

<div class="research-index">
  {% for project in site.data.research %}
    {% include research-card.html item=project number=forloop.index %}
  {% endfor %}
</div>

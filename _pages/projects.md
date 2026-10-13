---
layout: single
permalink: /projects/
title: "Engineering Projects"
description: "Engineering projects in numerical methods, aircraft design, structural analysis and experimental sensing."
author_profile: true
author: tanuj
---

<p class="section-introduction">These projects were undertaken to solve specific engineering problems, develop numerical tools or build and assess a design. For research questions that are still being investigated, see my <a href="{{ '/research/' | relative_url }}">Research page</a>.</p>

<div class="project-grid">
  {% for project in site.data.projects %}
    {% include project-card.html item=project %}
  {% endfor %}
</div>

---
layout: page
title: Projects
permalink: /projects/
description: Selected research and engineering work across computer vision, multimodal AI, foundation models, and real-world AI systems.
nav: true
nav_order: 2
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">

{% assign sorted_projects = site.projects | sort: "importance" %}

<div class="row row-cols-1 row-cols-md-3">
  {% for project in sorted_projects %}
    {% include projects.liquid %}
  {% endfor %}
</div>

</div>

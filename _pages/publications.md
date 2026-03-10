---
layout: page
permalink: /publications/
title: publications
description: Research publications and preprints.
nav: true
nav_order: 1
---

{% assign paper_projects = site.projects | where: "category", "paper" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-2">
{% for project in paper_projects %}
  {% include projects.liquid %}
{% endfor %}
</div>

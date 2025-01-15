---
title: Portfolio
layout: collection
permalink: /portfolio/
collection: portfolio
entries_layout: grid
classes: wide
---

My digital fabrication projects:
{% assign sorted_projects = site.projects | sort: "weight" %}
{% for project in sorted_projects %}
- [![{{ project.title }}]({{ project.image_path }})]({{ project.url }})
**{{ project.title }}**: {{ project.excerpt }}
{% endfor %}

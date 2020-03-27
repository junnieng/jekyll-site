---
layout: page
title: Collection
---
{% for part in site.gallery %}
  <h2>{{ part.name }}</h2>
  <p>{{ part.content }}</p>
{% endfor %}
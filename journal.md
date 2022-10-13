---
layout: default
title: "Journal"
---


{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Explore with me" %}
{% endif %}

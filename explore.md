---
layout: default
title: "Explore"
---
<a href="https://www.buymeacoffee.com/swanscodex" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/guidelines/download-assets-1.svg" alt="Buy Me A Coffee" height="80" width="300"></a>

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="The Codex" %}
{% endif %}

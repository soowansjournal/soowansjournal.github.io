---
layout: default
title: "Explore"
---
<a href="https://www.buymeacoffee.com/swanscodex" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="The Codex" %}
{% endif %}

---
layout: default
title: Starfsmenn
---
# Starfsmenn

<ul>
{% for author in site.authors %}
  <li>
    <h2>{{ author.name }}</h2>
    <h3>{{ author.position }}</h3>
    <p>{{ author.content | markdownify }}</p>
  </li>
{% endfor %}
</ul>
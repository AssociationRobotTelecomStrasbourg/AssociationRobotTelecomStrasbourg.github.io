---
layout: page
title: Équipe
permalink: /team/
---
{% for author in site.authors %}
- ## {{ author.name }}
  ### {{ author.position }}
  {{ author.content | markdownify }}
{% endfor %}

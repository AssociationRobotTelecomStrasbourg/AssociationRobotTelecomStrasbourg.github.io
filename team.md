---
layout: page
title: Équipe
permalink: /team/
---
<h1>///On tri par rôle ?///</h1>
{% for author in site.authors %}
- ## {{ author.name }}
  ### {{ author.position }}
  {{ author.content | markdownify }}
{% endfor %}

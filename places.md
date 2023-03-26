---
layout: page
title: Places
permalink: /places/
published: false
---

Here are some places:-
<ul>
{% for places in site.places %}
  <li><a href="{{ places.url }}">{{ places.name }}</a></li>
{% endfor %}
</ul>
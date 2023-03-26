---
layout: page
title: guides
permalink: /guides/
---

Below is a selection of guides I've put together for the city, if there is other things you are interested in let me know and I'll try and include it!

{% for guides in site.guides reversed %}
<a href="{{ guides.url }}">{{ guides.title }}</a> - Updated {{ guides.date | date: '%B %d, %Y' }}
{% endfor %}

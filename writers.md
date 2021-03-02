---
layout: default
title: Autoras
header: Autoras
description: Quienes participan
permalink: /writers/
---

Autoras de este proyecto:


{% for person in site.people %}
* <a href="{{ person.url | relative_url }}">{{ person.name }}</a>
{% endfor %}

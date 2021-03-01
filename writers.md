---
layout: default
title: Autoras
header: Autoras
description: Quienes participan
permalink: /writers/
---

Autoras de este proyecto:


{% for person in site.people %}
* <a href="{{ site.baseurl }}{{ person.url }}">{{ person.name }}</a>
{% endfor %}

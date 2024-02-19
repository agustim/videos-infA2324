---
title: CP Sarria Inf.A 23-24
logo: img/escut.png
layout: "base.njk"
---

## Partits

{% for partit in collections.partits %}
- [{{ partit.data.title }} ({{ partit.data.fecha }})]({{ partit.data.url }})
{% endfor %}


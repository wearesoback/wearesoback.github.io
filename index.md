---
layout: default
title: "Inicio"
---

## Posts Recientes
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

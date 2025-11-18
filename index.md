---
layout: default
title: "Inicio"
---

# Smoking Lopez  

Aquí va un texto que aún no he definido cual es, pero ya sabremos cual es.

## Posts Recientes
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

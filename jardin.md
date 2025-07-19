---
layout: default
title: Jardín de repos
permalink: /jardin/
---

# 🌿 Jardín de repos

Bienvenido al jardín. Aquí recolectamos dos tipos de proyectos open source:

## 🌱 Repos recientemente actualizados

{% for post in site.tags.jardin-reciente %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}

## 🌾 Repos olvidados o abandonados

{% for post in site.tags.jardin-abandonado %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
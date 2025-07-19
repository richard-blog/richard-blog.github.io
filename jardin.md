---
layout: default
title: Jardín de repos
permalink: /jardin/
---

# 🌿 Jardín de repos

Bienvenido al jardín. Aquí recolectamos dos tipos de proyectos open source:

## 🌱 Repos recientemente actualizados

{% for post in site.categories.repopublicoreciente %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}

## 🌾 Repos olvidados o abandonados

{% for post in site.categories.repopublicoabandonado %}
- [{{ post.title }}]({{ post.url }}) ({{ post.date | date: "%Y-%m-%d" }})
{% endfor %}
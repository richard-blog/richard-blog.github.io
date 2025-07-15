---
layout: default
title: Jardín de proyectos huérfanos
permalink: /jardin/
---

# 🌱 Jardín de proyectos huérfanos

Aquí recopilamos proyectos olvidados, abandonados o poco conocidos que merecen una segunda oportunidad. Cada uno fue analizado por IA y curado manualmente.

👇 Explorá las entradas más recientes:

<ul>
  {% for post in site.categories.jardin %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>
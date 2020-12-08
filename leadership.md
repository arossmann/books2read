---
layout: default
title: Leadership
weight: 4
---
# Leadership

<main class="shelf">
  {% for book in site.data.leadership  %}
    {% assign title=book.title %}
    {% assign author=book.author %}
    {% assign image=book.image %}
    {% assign link=book.link %}
    {% include book.html %}
  {% endfor %}
</main>
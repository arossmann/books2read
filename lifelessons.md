---
layout: default
title: Lessons for Life
weight: 6
---
# Lessons for Life

<main class="shelf">
  {% for book in site.data.lifelessions  %}
    {% assign title=book.title %}
    {% assign author=book.author %}
    {% assign image=book.image %}
    {% assign link=book.link %}
    {% include book.html %}
  {% endfor %}
</main>
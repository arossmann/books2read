---
layout: default
title: DevOps
weight: 3
---
# DevOps

<main class="shelf">
  {% for book in site.data.devops  %}
    {% assign title=book.title %}
    {% assign author=book.author %}
    {% assign image=book.image %}
    {% assign link=book.link %}
    {% include book.html %}
  {% endfor %}
</main>
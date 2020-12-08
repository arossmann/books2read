---
layout: default
title: Technology
weight: 7
---
# Technology

<main class="shelf">
  {% for book in site.data.technology  %}
    {% assign title=book.title %}
    {% assign author=book.author %}
    {% assign image=book.image %}
    {% assign link=book.link %}
    {% include book.html %}
  {% endfor %}
</main>
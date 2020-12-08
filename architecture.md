---
layout: default
title: Architecture
weight: 2
---
# Architecture

<main class="shelf">
  {% for book in site.data.architecture %}
    {% assign title=book.title %}
    {% assign author=book.author %}
    {% assign image=book.image %}
    {% assign link=book.link %}
    {% include book.html %}
  {% endfor %}
</main>

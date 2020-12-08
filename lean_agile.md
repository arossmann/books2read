---
layout: default
title: Lean / Agile
weight: 5
---
# Lean / Agile

<main class="shelf">
  {% for book in site.data.lean_agile  %}
    {% assign title=book.title %}
    {% assign author=book.author %}
    {% assign image=book.image %}
    {% assign link=book.link %}
    {% include book.html %}
  {% endfor %}
</main>
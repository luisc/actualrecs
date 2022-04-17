---
layout: page
title: Film
category-name: Film
permalink: "/topics/film/"
summary: Actual Recommendations for videos about films, usually making ofs and some theory and critique
image: https://i.imgur.com/FKIKlUO.jpg
---

> Everything from the **making of a movie**, to **film theory** to a **good review** of a film.
>
> On occasion, an entire movie 📽

{% for post in site.categories.film %}
  {% include article.html post=post %}
{% endfor %}

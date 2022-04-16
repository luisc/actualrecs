---
layout: page
category-name: Film
permalink: "/topics/film/"
---

# {{ page.category-name }}

> Everything from the **making of a movie**, to **film theory** to a **good review** of a film.
>
> On occasion, an entire movie 📽

{% for post in site.categories.film %}
  {% include article.html post=post %}
{% endfor %}

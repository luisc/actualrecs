---
layout: page
category-name: Music
permalink: "/topics/music/"
---

# {{ page.category-name }}

> Mostly **short documentaries about music**: musicians, bands, genres.
>
> Sometimes just a great song or album from an underappreciated artist or compilation 🎵

{% for post in site.categories.music %}
  {% include article.html post=post %}
{% endfor %}

---
layout: page
title: Music
category-name: Music
permalink: "/topics/music/"
summary: Actual Recommendations for videos about music, musicians, bands and genres
image: https://i.imgur.com/NveTaAE.jpg
---

> Mostly **short documentaries about music**: musicians, bands, genres.
>
> Sometimes just a great song or album from an underappreciated artist or compilation 🎵

{% for post in site.categories.music %}
  {% include article.html post=post %}
{% endfor %}

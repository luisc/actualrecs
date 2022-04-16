---
layout: page
category-name: Cooking
permalink: "/topics/cooking/"
---

# {{ page.category-name }}

> Cooking AND Baking, sometimes they are one and the same.
>
> If you are looking to get started, or you want some new ideas - there's some great stuff here 🍳

## Posts

{% for post in site.categories.cooking %}
 * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: site.date_format }}
{% endfor %}

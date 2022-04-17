---
layout: page
title: Economics
category-name: Economics
permalink: "/topics/economics/"
summary: Actual Recommendations for videos about economics, mostly macro and theory
image: https://i.imgur.com/3kYnJll.jpg
---

> Stock market stuff, macroeconomics, theory of money. 
>
> Probably a healthy dose of wealth inequality stuff too 💸

{% for post in site.categories.economics %}
  {% include article.html post=post %}
{% endfor %}

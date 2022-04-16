---
layout: page
category-name: Economics
permalink: "/topics/economics/"
---

# {{ page.category-name }}

> Stock market stuff, macroeconomics, theory of money. 
>
> Probably a healthy dose of wealth inequality stuff too 💸

{% for post in site.categories.economics %}
  {% include article.html post=post %}
{% endfor %}

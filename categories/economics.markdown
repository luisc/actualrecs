---
layout: page
category-name: Economics
permalink: "/topics/economics/"
---

# {{ page.category-name }}

> Stock market stuff, macroeconomics, theory of money. 
>
> Probably a healthy dose of wealth inequality stuff too 💸

## Posts

{% for post in site.categories.economics %}
 * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: site.date_format }}
{% endfor %}

---
layout: page
category-name: Fun
permalink: "/topics/fun/"
---

# {{ page.category-name }}

> This is anything and everything fun, bizarre and DOPE!
>
> That's not to say the other ActualRecs aren't fun, but this stuff definitely is 😸

{% for post in site.categories.fun %}
  {% include article.html post=post %}
{% endfor %}

---
layout: page
title: Fun
category-name: Fun
permalink: "/topics/fun/"
summary: Actual Recommendations for fun videos, cats being weirdos to anything and everything bizarre and DOPE!
image: https://i.imgur.com/OQRgkgG.jpg
---

> This is anything and everything fun, bizarre and DOPE!
>
> That's not to say the other ActualRecs aren't fun, but this stuff definitely is 😸

{% for post in site.categories.fun %}
  {% include article.html post=post %}
{% endfor %}

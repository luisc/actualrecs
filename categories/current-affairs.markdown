---
layout: page
title: Current Affairs
category-name: Current Affairs
permalink: "/topics/current-affairs/"
summary: Actual Recommendation for videos about the world now and the recent past.
image: https://i.imgur.com/CITaRUB.jpg
---

> So these posts aren't *necessarily current*, but I wasn't sure what else to call it.
>
> It might be something happening now, it might also be something from the 90s. Then again the 90s don't seem like they were very long ago to me 🕴️

{% for post in site.categories["Current Affairs"] %}
  {% include article.html post=post %}
{% endfor %}

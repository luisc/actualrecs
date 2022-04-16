---
layout: page
category-name: History
permalink: "/topics/history/"
---

# {{ page.category-name }}

> Anything about 1960s and before. Ancient history stuff too.
>
> Finding good sourced stuff without ridiculous history channel style re-enactments can be a challenge, but we'll see what we can do 📜

## Posts

{% for post in site.categories.history %}
 * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: site.date_format }}
{% endfor %}

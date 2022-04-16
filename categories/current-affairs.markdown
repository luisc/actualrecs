---
layout: page
category-name: Current Affairs
permalink: "/topics/current-affairs/"
---

# {{ page.category-name }}

> So these posts aren't *necessarily current*, but I wasn't sure what else to call it.
>
> It might be something happening now, it might also be something from the 90s. Then again the 90s don't seem like they were very long ago to me 🕴️

## Posts

{% for post in site.categories["Current Affairs"] %}
 * [{{ post.title }}]({{ post.url }}) - {{ post.date | date: site.date_format }}
{% endfor %}

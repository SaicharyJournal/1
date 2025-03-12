---
layout: default
title: "Blog"
permalink: /blog/
---

# Welcome to My Blog ✍️

I love writing about technology, travel, and personal growth. Here are my latest posts:

{% for post in site.posts %}
- **[{{ post.title }}]({{ post.url }})** - *{{ post.date | date: "%B %d, %Y" }}*
{% endfor %}

Stay tuned for more updates!

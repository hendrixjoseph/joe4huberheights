---
layout: template
title: Blog Posts
---

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }}) posted on {{ post.date | date: "%B %e, %Y" }}
{% endfor %}
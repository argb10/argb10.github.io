---
layout: papermod
title: "~/blog"
permalink: /blog/
profile: false
---

## Recent posts

{% for post in site.posts limit: 20 %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}

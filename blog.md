---
layout: default
title: Naz Malik | Blog
---

{% include page_head.html %}

# Blog

{% for post in site.categories.tech %}
- `{{ post.date | date: "%d-%m-%Y" }}` - [{{ post.title }}]({{ post.url }}) {% endfor %}

[Subscribe with rss](/feed.xml)

---
layout: default
title: Naz Malik | Blog
---

{% include page_head.html %}

# Blog

{% for post in site.categories.tech %}
- `{{ post.date | date: "%d-%m-%Y" }}` - [{{ post.title }}]({{ post.url }}) {% endfor %}

I also wrote a bunch of blog posts while I was taking my first steps in programming at [Makers Academy](http://www.makersacademy.com/). They now make me cringe a little. You can find them [here](https://medium.com/@nazwhale).

[Subscribe with rss](/feed.xml)

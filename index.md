---
# You don't need to edit this file, it's empty on purpose.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Naz Malik | Naz Malik
---

# Naz Malik

Do-er of bits and bobs at [Monzo](https://monzo.com/), ex-writer for Canvas and [Music is My Sanctuary](http://www.musicismysanctuary.com/), alumnus of [Makers Academy](http://www.makersacademy.com/) and University College London.

- [Github](https://github.com/nazwhale)

## Blog

[All posts](/blog.html)
{% for post in site.categories.tech limit: 3 %}
- `{{post.date | date: "%d-%m-%Y"}}` - [{{ post.title }}]({{ post.url }}) {% endfor %}

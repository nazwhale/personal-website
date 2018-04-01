---
# You don't need to edit this file, it's empty on purpose.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Naz Malik | Naz Malik
---

# Naz Malik

Do-er of bits and bobs at [Monzo](https://monzo.com/), ex-writer for Canvas and [Music is My Sanctuary](http://www.musicismysanctuary.com/), alumnus of [Makers Academy](http://www.makersacademy.com/) and University College London.

Currenly: 
- Trying to crack React
- Dipping my toes into Go
- Getting my head around concurrency

## Blog

[All posts](/blog/blog.html)
{% for post in site.categories.tech limit: 3 %}
- `{{post.date | date: "%d-%m-%Y"}}` - [{{ post.title }}]({{ post.url }}) {% endfor %}

## Projects

- [Tic-Tac-Toe](https://github.com/nazwhale/Tic-Tac-Toe), a command-line game of tic-tac-toe, with an invincible computer player. For the AI, I used the Negamax algorithm with alpha-beta pruning.
- [Nazbot](https://github.com/nazwhale/nazbot), a Twitter bot that replies to tweets with relevant news articles.
- [Smart Rockets](https://github.com/nazwhale/smart-rockets), a Twitter bot that replies to tweets with relevant news articles.

---
  
**@**
[Github](https://github.com/nazwhale/) 
[Twitter](https://twitter.com/nazwhale/)

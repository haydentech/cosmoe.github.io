---
layout: home
title: Cosmoe
---

Welcome to Cosmoe.

Cosmoe is an open-source, cross-platform C++ framework inspired by BeOS/Haiku,
bringing its powerful but easy-to-use class library to Linux, Mac, and Windows systems.

## Latest News

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url | relative_url }})

{{ post.excerpt }}

{% endfor %}

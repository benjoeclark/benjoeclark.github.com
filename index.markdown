---
layout: default
title: benjoeclark
---

{% for post in site.posts limit:5 %}

posts
=====
[{{ post.title }}]({{ post.url }})
----------------------------------
{{ post.content }}
*posted on {{ post.date | date_to_long_string }}*

{% endfor %}

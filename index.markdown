---
layout: default
title: benjoeclark
---

posts
=====
{% for post in site.posts limit:5 %}

[{{ post.title }}]({{ post.url }})
----------------------------------
*posted on {{ post.date | date_to_long_string }}*

{% endfor %}

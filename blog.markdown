---
layout: default
title: benjoeclark blog
---

{% for post in site.posts %}

[{{ post.title }}]({{ post.url }})
----------------------------------
{{ post.content }}
*posted on {{ post.date | date_to_long_string }}*

{% endfor %}

---
layout: default
title: "所有文章"
permalink: /posts/
---

# 所有文章

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

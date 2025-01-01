---
layout: default
title: "Oreki小型日记本"
permalink: /posts/
---

# Oreki小型日记本

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}

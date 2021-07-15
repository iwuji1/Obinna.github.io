---
layout: default
title: Blog
permalink: /blog
---

# My Blog Posts

<div class="main-blog">
  {% for post in site.posts %}
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <hr>
  {% endfor %}
</div>

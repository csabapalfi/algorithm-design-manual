---
layout: default
title: Algorithm Design Manual notes
root: true
---

<ul class="posts">
  {% for post in site.posts reversed %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
---
layout: index
---

My work-in-progress notes for the book titled '[The Algorithm Design Manual](http://www.algorist.com/)' by Steven S. Skiena.

<ul class="posts">
  {% for post in site.posts reversed %}
    <li><a href=".{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
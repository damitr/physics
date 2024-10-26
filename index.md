---
layout: default
title: Home
---

# Welcome to My Physics Blog

This is a space to discuss principles, problems, perspectives, practices, philosophy, and pedagogy of physics.

## Recent Posts

<ul>
  {% for post in site.posts %}
    <li><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}</li>
  {% endfor %}
</ul>

Feel free to explore and share your thoughts!

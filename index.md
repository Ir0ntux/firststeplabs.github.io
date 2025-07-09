---
layout: default
title: Blog
---

# 📚 First Step Labs Blog

Welcome to my blog where I document my cybersecurity journey.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

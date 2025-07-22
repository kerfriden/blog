---
layout: default
title: Home
---

# 📝 Welcome to My Blog

This is a simple blog built with **Jekyll** and hosted on **GitHub Pages**.

## 📚 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

---
layout: default
title: Home
---

# 📝 Welcome to my Professional Blog

On this website, you will find posts related to my group's research and scientific activity, as well as links to teaching material

## 📁 Pages

- [Teaching](/blog/teaching/)
- [About](/blog/about/)
- [Contact](/blog/contact/)

## 📚 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

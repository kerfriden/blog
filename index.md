---
layout: default
title: Home
---

# 📝 Welcome to my Blog

On this website, you will find posts related to my group's research and scientific activities, as well as links to reasearch and teaching material that yuo may find useful

## 📁 Pages

- [Teaching](/teaching/)
- [About](/about/)
- [Contact](/contact/)

## 📚 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

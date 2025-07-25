---
layout: default
title: Posts
permalink: /blog/
---

## 📚 Latest Posts


<h2>Latest posts</h2>
{% for post in site.posts limit:5 %}
  <article>
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small>{{ post.date | date: "%B %-d, %Y" }}</small></p>
    <div>
      {{ post.content }}
    </div>
    <hr>
  </article>
{% endfor %}


<h2>All posts</h2>
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>


---
layout: default
title: Home
---

## 🏠 Welcome!  
 
On this website, you will find posts related to my group's research and scientific activities, as well as links to reasearch and teaching material that you may find useful 

<!--
## 📁 Pages 
 
- [About](/about/) 
- [Contact](/contact/)
- [Teaching](/teaching/)
- [Job Offers](/job-offers/) 
-->

## 📚 Scientific Publications

- [Publication list](/publications/)
- [Google Scholar Profile](https://scholar.google.com/citations?hl=en&user=EV2wmsgAAAAJ&view_op=list_works&sortby=pubdate)

## 📚 Other links

- [Centre des Matériaux on LinkedIn](https://www.linkedin.com/company/centre-des-materiaux-mines-paris/?viewAsMember=true)
- [SIMS Research Group](/SIMS/)
- [My old website 😖](https://computationalengin.blogspot.com/)

## 📚 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>





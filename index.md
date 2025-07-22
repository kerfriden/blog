---
layout: default
title: Home
---

# 🏠 Welcome

On this website, you will find posts related to my group's research and scientific activities, as well as links to reasearch and teaching material that you may find useful

## 📁 Pages

- [About](/blog/about/)
- [Teaching](/blog/teaching/)
- [Job Offers](/blog/job_offers/)

## 📚 Scientific Publications

[Google Scholar Profile](https://scholar.google.com/citations?hl=en&user=EV2wmsgAAAAJ&view_op=list_works&sortby=pubdate)

## 📚 Liens divers

- [My previous website](https://computationalengin.blogspot.com/)
- [Centre des Matériaux](https://www.linkedin.com/company/centre-des-materiaux-mines-paris/?viewAsMember=true)

## You can reach me at:

- 📧 pierre.kerfriden at minesparis.psl dot eu
- 💼 [LinkedIn](https://www.linkedin.com/in/pierrekerfriden/?originalSubdomain=fr)

## 📚 Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>





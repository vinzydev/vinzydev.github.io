---
layout: page
title: "Blog"
permalink: /blog/
---

# Tech Blog

Welcome to my tech blog where I share insights on cloud computing, DevOps practices, and the latest trends in technology.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

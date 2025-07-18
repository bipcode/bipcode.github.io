---
layout: default
title: Home
nav_order: 1
---

# Who am I?
{: .fs-9 }

I am just a guy who loves tinkering with machines, computers and circuit boards. 
# Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>{{ post.date | date: "%Y-%m-%d" }}</small>
    </li>
  {% endfor %}
</ul>

---
layout: default
title: Archive
permalink: /archive/
---

# All Activity

Welcome to the archive of all blog posts. Here you will find a list of all the posts in chronological order.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><small><em>{{ post.date | date: "%B %d, %Y" }}</em></small></p>
      <div>{{ post.content }}</div>
    </li>
  {% endfor %}
</ul>

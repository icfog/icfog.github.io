---
layout: default
title: Post Archive
permalink: /post-archive/
---

# Post Archive

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><small><em>{{ post.date | date: "%B %d, %Y" }}</em></small></p>
      <div>{{ post.content }}</div>
    </li>
  {% endfor %}
</ul>

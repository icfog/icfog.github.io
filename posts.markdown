---
layout: archive
title: Posts
permalink: /posts/
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><small><em>{{ post.date | date: "%B %d, %Y" }}</em></small></p>
    </li>
  {% endfor %}
</ul>

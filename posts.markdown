---
layout: default
title: posts
permalink: /posts/
---
<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p><small><em>{{ post.date | date: "%B %d, %Y" }}</em> by {{ post.author }}</small></p>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>

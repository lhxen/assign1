---
layout: page
title: Blog
---

# Blog Posts

Welcome to my blog! Here I share my thoughts and experiences about software development, technology trends, and best practices.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
      <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
    </li>
  {% endfor %}
</ul> 
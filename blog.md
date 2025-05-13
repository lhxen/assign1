---
layout: page
title: Blog
---

<div class="blog-section">
    <h1>Blog Posts</h1>
    <p>Welcome to my blog! Here I share my thoughts and experiences about software development, technology trends, and best practices.</p>

    <div class="post-list">
        {% for post in site.posts %}
        <div class="post-item">
            <h2><a href="{{ post.url | relative_url }}" class="post-link">{{ post.title }}</a></h2>
            <p class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</p>
            <p class="post-excerpt">{{ post.excerpt }}</p>
        </div>
        {% endfor %}
    </div>
</div> 
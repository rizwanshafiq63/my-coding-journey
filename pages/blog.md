---
title: "My Blogs"
---

# 📝 My Blogs

Welcome to my blog section! Here, I share my thoughts, projects, and learning journey.  

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - <small>{{ post.date | date: "%B %d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

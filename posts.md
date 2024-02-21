---
title: "Posts by Category"
layout: categories
#permalink: /posts/
author_profile: true
---

  {% for post in site.posts %}
      <a href="{{ post.url }}">{{ post.title }}{{ post.content}}</a>
    
  {% endfor %}

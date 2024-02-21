---
title: "Posts by Category"
layout: categories
permalink: /posts/
author_profile: true
---
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}{{ post.categories }}</a>
    </li>
  {% endfor %}
</ul>
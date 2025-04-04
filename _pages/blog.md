---
layout: single
title: "Blog Posts"
permalink: /blog/
author_profile: true
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.posts %}
    {% if post.categories contains 'blog' or post.tags contains 'blog' %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div> 
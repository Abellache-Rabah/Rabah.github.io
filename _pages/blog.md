---
layout: archive
title: "Blog Posts"
permalink: /blog/
author_profile: true
---

{% include base_path %}

{% for post in site.posts %}
  {% if post.categories contains 'blog' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %} 
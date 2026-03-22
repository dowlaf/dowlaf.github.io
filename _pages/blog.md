---
layout: archive
title: "Backpacking blog"
permalink: /backpacking/
author_profile: false
entries_layout: grid
classes: wide
---

I like to write about my backpacking trips. All except the most recent posts are daily blog posts from my 2025 through hike of the Pacific Crest Trail. 


{% assign posts = site.categories.backpacking %}
{% for post in posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}

One day this page will be more organized...
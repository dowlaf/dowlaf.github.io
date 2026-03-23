---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: True
entries_layout: grid
classes: wide
---

I like to write about my backpacking trips. All except the most recent posts are daily blog posts from my 2025 through hike of the Pacific Crest Trail. 


{% assign posts = site.categories.backpacking %}
{% for post in posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
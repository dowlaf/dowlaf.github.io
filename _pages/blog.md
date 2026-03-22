---
layout: archive
title: "Backpacking blog"
permalink: /backpacking/
author_profile: true
entries_layout: grid
classes: wide
---

Test

Number of backpacking posts found: {{ site.categories.backpacking | size }}
{% assign posts = site.categories.backpacking %}
{% for post in posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
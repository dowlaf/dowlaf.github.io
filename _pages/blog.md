---
layout: archive
title: "Backpacking blog"
permalink: /backpacking/
author_profile: true
entries_layout: grid
classes: wide
---

Test

{% assign posts = site.categories.Backpacking %}
{% for post in posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
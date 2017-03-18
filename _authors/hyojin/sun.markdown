---
title: Sun
date: 2017-03-18 00:10:00 +00:00
position: 0
---

{% assign sorted_authors = site.authors | sort:"position" %}
{% for author in sorted_authors %}
  <li>{{ author.title }}</li>
{% endfor %}

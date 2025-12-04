---
title: "Publications"
permalink: /publications/
layout: single
author_profile: true
---

## Publications

<style>
.pub-list { font-size: 0.9rem; line-height: 1.5; padding-left: 1.2em; }
.pub-list li { margin-bottom: 0.4rem; }
.pub-list a { font-weight: 600; }
</style>

<ul class="pub-list">
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for pub in pubs %}
  <li><a href="{{ pub.url | relative_url }}">{{ pub.title }}</a> — {{ pub.authors }}</li>
{% endfor %}
</ul>

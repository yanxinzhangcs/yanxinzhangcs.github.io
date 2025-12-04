---
title: "Publications"
permalink: /publications/
layout: single
author_profile: true
---

## Publications

<style>
.pub-list { font-size: 0.95rem; line-height: 1.5; }
.pub-list a { font-weight: 600; }
</style>

<div class="pub-list">
{% assign pubs = site.publications | sort: "date" | reverse %}
{% for pub in pubs %}
- [{{ pub.title }}]({{ pub.url | relative_url }}) — {{ pub.authors }}
{% endfor %}
</div>

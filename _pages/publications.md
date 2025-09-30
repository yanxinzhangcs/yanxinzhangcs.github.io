---
title: "Publications"
permalink: /publications/
layout: archive
author_profile: true
entries_layout: grid 
show_excerpts: true 
---

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
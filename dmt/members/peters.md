---
title: "Members > Diana Peters"
permalink: /dmt/members/~peters/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Peters' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

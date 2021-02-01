---
title: "Members > Wenjun Huang"
permalink: /dmt/members/~huang/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Huang' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

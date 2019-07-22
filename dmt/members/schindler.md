---
title: "Members > Sirko Schindler"
permalink: /dmt/members/~schindler/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Schindler' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

---
title: "Members > Sirko Schindler"
permalink: /mma/members/~schindler/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Schindler' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

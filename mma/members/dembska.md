---
title: "Members > Dr. Marta Dembska"
permalink: /mma/members/~dembska/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Dembska' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

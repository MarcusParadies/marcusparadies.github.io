---
title: "Members > Arne Osterthun"
permalink: /dzv/members/~osterthun/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Osterthun' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

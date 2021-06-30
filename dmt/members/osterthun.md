---
title: "Members > Arne Osterthun"
permalink: /dmt/members/~osterthun/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Osterthun' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

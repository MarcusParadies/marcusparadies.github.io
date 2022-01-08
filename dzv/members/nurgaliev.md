---
title: "Members > Azat Nurgaliev"
permalink: /dzv/members/~nurgaliev/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Nurgaliev' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

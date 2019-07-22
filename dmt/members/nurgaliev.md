---
title: "Members > Azat Nurgaliev"
permalink: /dmt/members/~nurgaliev/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Nurgaliev' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

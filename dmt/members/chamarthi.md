---
title: "Members > Sireesha Chamarthi"
permalink: /dmt/members/~chamarthi/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Chamarthi' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

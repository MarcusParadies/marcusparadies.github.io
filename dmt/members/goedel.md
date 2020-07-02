---
title: "Members > Michael Gödel"
permalink: /dmt/members/~goedel/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Gödel' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

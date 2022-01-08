---
title: "Members > Joshua Reibert"
permalink: /dzv/members/~reibert/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Reibert' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

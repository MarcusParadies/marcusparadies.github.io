---
title: "Members > Constantin Pestka"
permalink: /ins/members/~pestka/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Pestka' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

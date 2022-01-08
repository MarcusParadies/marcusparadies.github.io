---
title: "Members > Bara' Al-Bataineh"
permalink: /ins/members/~al-bataineh/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Al-Bataineh' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

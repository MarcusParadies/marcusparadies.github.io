---
title: "Members > Bara' Al-Bataineh"
permalink: /dmt/members/~albataineh/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Al-Bataineh' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

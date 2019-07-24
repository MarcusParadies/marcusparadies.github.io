---
title: "External Collaborators > Hani Al-Sayeh"
permalink: /dmt/members/~al-sayeh/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Al-Sayeh' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

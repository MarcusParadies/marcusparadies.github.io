---
title: "External Collaborators > Stefan Hagedorn"
permalink: /dmt/members/~hagedorn/
---

[Research Profile](https://www.tu-ilmenau.de/dbis/staff/stefan-hagedorn/)

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Hagedorn' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

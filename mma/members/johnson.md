---
title: "External Collaborators > Dr. Michael Johnson"
permalink: /mma/members/~johnson/
---

[Research Profile](https://www.mpifr-bonn.mpg.de/person/109206/632489)

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Johnson' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

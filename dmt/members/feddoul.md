---
title: "External Collaborators > Leila Feddoul"
permalink: /dmt/members/~feddoul/
---

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Feddoul' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

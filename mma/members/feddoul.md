---
title: "External Collaborators > Leila Feddoul"
permalink: /mma/members/~feddoul/
---

[Research Profile](https://fusion.cs.uni-jena.de/fusion/members/feddoul-leila/)

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Feddoul' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

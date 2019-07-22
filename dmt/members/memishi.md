---
title: "Dr. Bunjamin Memishi"
collection: members
permalink: /dmt/members/~memishi
---

[[CV]](https://marcusparadies.github.io/files/people/memishi/CV.pdf)

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Memishi' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

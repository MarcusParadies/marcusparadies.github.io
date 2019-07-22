---
title: "Members > Dr. Bunjamin Memishi"
collection: members
permalink: /dmt/members/~memishi
---

## Bio

[[CV]](https://marcusparadies.github.io/files/people/memishi/CV.pdf)

## Recent Publications

{% for post in site.publications reversed %}
  {% if post.authors contains 'Memishi' %}
    {% include archive-compact.html %}
  {% endif %}
{% endfor %}

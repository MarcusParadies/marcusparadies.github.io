---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my articles on my [Google Scholar profile](https://scholar.google.de/citations?user=psFgGl8AAAAJ&hl=de) or my [DBLP profile](https://dblp.uni-trier.de/pers/hd/p/Paradies:Marcus).

{% include base_path %}

{% for post in site.publications reversed %}
  {% if post.author contains 'Paradies' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

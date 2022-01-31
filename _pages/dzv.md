---
layout: archive
title: "Data Access and Processing Group"
permalink: /dzv/
---
<p align="justify">
Modern database management systems nowadays have to cope with diverse challenges: (1) Data is becoming increasingly heterogeneous (e.g., raster data, timeseries data, and point cloud data) and is created in different volumes and velocities, (2) data access patterns are increasingly diverse and interactive (e.g., through the usage of mobile end devices, interactive data exploration, and the direct access to data through virtual research environments), and (3) database management systems have to run in diverse execution environments (e.g., cloud, edge, embedded). For such manifold requirements today’s database management systems are not designed for in their entirety.</p>

<p align="justify">
Based on these requirements, the research group develops methods and technologies, which allow storing diverse data sets in a database management system and simultaneously provide efficient data access methods. Herein, in particular aspects of performance, scalability (with respect to data volume and available hardware resources), and resource efficiency, play a crucial role. In addition, the research is conducted by considering recent trends, e.g., the diversification of the compute- and storage hardware landscape (e.g., NVMe SSDs, persistent memory, computational storage) as well as different usage scenarios during the architectural design of the systems.</p>

## Members

* Marcus Paradies (acting group lead)
* [Azat Nurgaliev](https://marcusparadies.github.io/dzv/members/~nurgaliev/)
* [Arne Osterthun](https://marcusparadies.github.io/dzv/members/~osterthun/)
* [Joshua Reibert](https://marcusparadies.github.io/dzv/members/~reibert/)

## Recent Publications
  <ul>{% for post in site.publications reversed %}
    {% if post.tag contains "dzv" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
## Projects

{% for post in site.portfolio %}
  {% if post.active == "yes" and post.tag contains 'dzv' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

## Job Offerings
Are you a student looking for BSc/MSc thesis projects? Contact [me](mailto:marcus.paradies@dlr.de) for a list of available topics on large-scale data management.


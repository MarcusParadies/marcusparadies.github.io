---
layout: archive
title: "Metadata Management Group"
permalink: /mma/
---
<p align="justify">
Data is becoming the main driver in an increasing number of areas within both academia and industry. Integrating and leveraging data from both public and private sources leads to new discoveries, enables pioneering developments, and results in innovative products. With stakeholders growing in number and variety, the data landscape gets ever more diverse, rich, and interesting. However, this increasing heterogeneity in users and data also gives rise to new challenges:
Data descriptions need to serve a general audience instead of just a single project;
Suitable datasets need to be identified amongst myriads of potential candidates and sources;
The understanding of terms and concepts varies between different stakeholders and needs to be matched to one another.
</p>

<p align="justify">
While the Semantic Web promises to alleviate these and other challenges, we are not quite there yet and the full potential of data-driven research and economy is still to be unleashed..
</p>

<p align="justify">
The central theme of the group is making data available not just its initial context but beyond the boundaries of projects, institutions, and communities. In collaboration with our partners, our activities revolve around the following key research areas and questions:

* Metadata
  * Which properties are essential or provide benefits to future users?
  * What support can we give to users when describing their data?
  * How can we seamlessly document the history of datasets, their provenance?
* Semantic Web & Knowledge Graphs
  * What is needed to mediate between different stakeholders along the data life cycle?
  * How can Knowledge Graphs evolve reflecting changing user demands?
* Data Management in Research and Industry
  * What is necessary to establish proper data management practices?
  * Which assistance can tools provide to users and data curators in their daily data-tasks?
* Added Value
  * What other services can we build on top of knowledge graphs and semantic metadata to support users?
</p>

## Members

* [Sirko Schindler (group lead)](https://marcusparadies.github.io/mma/members/~schindler/)
* [Marta Dembska](https://marcusparadies.github.io/mma/members/~dembska/)
* [Michael Gödel](https://marcusparadies.github.io/mma/members/~goedel/)

## External Collaborators

* [Leila Feddoul (FSU Jena)](https://marcusparadies.github.io/mma/members/~feddoul/)
* [Michael Johnson (MPIfR)](https://marcusparadies.github.io/mma/members/~johnson/)

## Recent Publications
  <ul>{% for post in site.publications reversed %}
    {% if post.tag contains "mma" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  

## Projects

{% for post in site.portfolio %}
  {% if post.active == "yes" and post.tag contains "mma" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

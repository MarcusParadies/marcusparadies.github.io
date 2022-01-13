---
layout: archive
title: "Information Extraction and Interoperability Group"
permalink: /ixi/
---

<p align="justify">
Information and data exchange is essential for communication in a wide variety of areas; for example, between companies regarding production data or between research institutions regarding measurement and survey data.
</p>

<p align="justify">
This exchange is made more difficult by the fact that information and data are available in incompatible and sometimes not even machine-readable formats. For example, they are often stored in - from the computer's point of view - unstructured or semi-structured documents.
</p>

<p align="justify">
In order to simplify the exchange of information and to make unstructured data accessible for further automated processing, the working group is therefore pursuing two main research areas:
* Information extraction (primarily (further) development of natural language processing methods on documents)
* Interoperability, especially at the semantic level
  * Development of methods and tools for the (semi-)automatic creation and extension of semantic models as a basis for interoperability
  * Development of methods and tools for automatic matching of needs and capabilities/offers, for example along supply chains, recycling chains, etc.
</p>

## Members

* [Diana Peters (group lead)](https://marcusparadies.github.io/dmt/members/~peters/)

## External Collaborators

## Recent Publications
  <ul>{% for post in site.publications reversed %}
    {% if post.tag contains "ixi" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  

## Projects

{% for post in site.portfolio %}
  {% if post.active == "yes" and post.tag contains "ixi" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

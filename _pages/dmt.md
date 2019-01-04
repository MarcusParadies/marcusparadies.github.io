---
layout: archive
title: "Data Management Technologies Group"
permalink: /dmt/
---

The ubiquitous data deluge poses tremendous challenges for efficient data access, data management, and data archiving and is a key driver for the rapid development and evolvement of modern data platforms.  The sheer explosion of data volumes and growing data veracity as well as increasingly heterogeneous data sources and applications call for novel methods and system architectures in the management of big data. As an immediate consequence, the processing paradigm mutates from "processing-focused", i.e., the data is moved to the processing facilities, into "data-focused", where the processing is moved to where the data resides. Based on concrete use cases and requirements of management of earth observation data, the research group develops novel methods and system concepts, which shall result in practical system developments for the corresponding institutions.

In this context, novel methods for storage and processing strategies for large volumes of heterogeneous, multi-dimensional data in distributed IT infrastructures, such as public/private clouds, are the main research areas of the group. In particular, the volume, veracity, and variety of data pose challenges for efficient data access methods. Multi-dimensional index structures and semantic annotations based on knowledge models are the key components that allow identifying and locating relevant data sets more efficiently. Data access itself can be further improved by leveraging domain-specific characteristics to improve data organization in the storage hierarchy and by taking potentially conflicting data access patterns into account. Ultimately, this enables the development of flexible yet efficient data exploitation platforms, which can handle large volumes of heterogeneous data while providing efficient data access and processing capabilities.

The research is conducted in collaboration with the [German Remote Sensing Data Center](https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-5278/8856_read-15911/) in Oberpfaffenhofen and the academic collaborators from the [Technische Universität Ilmenau](https://www.tu-ilmenau.de/dbis/) and the [Friedrich-Schiller Universität Jena](http://fusion.cs.uni-jena.de/fusion/).

Recent Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

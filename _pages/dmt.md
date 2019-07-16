---
layout: archive
title: "Data Management Technologies Group"
permalink: /dmt/
---

The ubiquitous data deluge poses tremendous challenges for efficient data access, data management, and data archiving and is a key driver for the rapid development and evolvement of modern data platforms.  The sheer explosion of data volumes and growing data veracity as well as increasingly heterogeneous data sources and applications call for novel methods and system architectures in the management of big data. As an immediate consequence, the processing paradigm mutates from "processing-focused", i.e., the data is moved to the processing facilities, into "data-focused", where the processing is moved to where the data resides. Based on concrete use cases and requirements of management of earth observation data, the research group develops novel methods and system concepts, which shall result in practical system developments for the corresponding institutions.

In this context, novel methods for storage and processing strategies for large volumes of heterogeneous, multi-dimensional data in distributed IT infrastructures, such as public/private clouds, are the main research areas of the group. In particular, the volume, veracity, and variety of data pose challenges for efficient data access methods. Multi-dimensional index structures and semantic annotations based on knowledge models are the key components that allow identifying and locating relevant data sets more efficiently. Data access itself can be further improved by leveraging domain-specific characteristics to improve data organization in the storage hierarchy and by taking potentially conflicting data access patterns into account. Ultimately, this enables the development of flexible yet efficient data exploitation platforms, which can handle large volumes of heterogeneous data while providing efficient data access and processing capabilities.

The research is conducted in collaboration with the [German Remote Sensing Data Center](https://www.dlr.de/eoc/en/desktopdefault.aspx/tabid-5278/8856_read-15911/) in Oberpfaffenhofen and the academic collaborators from the [Technische Universität Ilmenau](https://www.tu-ilmenau.de/dbis/) and the [Friedrich-Schiller Universität Jena](http://fusion.cs.uni-jena.de/fusion/).

## Recent Publications
{% assign oldyr = 5000 %}
  <ul>{% for post in site.publications reversed %}
    {% if post.tag == "dmt" %}
      {% assign newyr = post.date | default: "1900-01-01" | date: "%Y" %}
      {% include archive-single-cv.html %}
  <b> Test1 </b>
    {% endif %}
  {% endfor %}</ul>

## Projects

### CryoDrill

Modern high-resolution observational instruments and complex models of the earth system and of physical, chemical, and biological processes generate multiple hundreds of petabytes of scientific data per year. Digital data archives store such scientific data in private clouds for further investigation and long-term preservation, and disseminate it through data platforms via order-based catalogs. To reduce the total cost of ownership, such data platforms employ hierarchical storage management with large, disk-based caches and robotic tape libraries. Prefetching all the data from a slower storage layer is typically not possible due to the ad-hoc nature of scientific analyses and the size of the required data set to achieve satisfactory results for long-term trend analysis and prediction. Consequently, data movement is one of the most time- and energy-consuming tasks for data-intensive, scientific workflows. Near-data processing (NDP) has been advocated to reduce the amount of data to be transferred as early as possible. Unfortunately, for large-scale scientific data, this only benefits faster layers of the storage hierarchy. In a deep storage hierarchy, as it is common for active data archives, NDP can be even more beneficial if pushed further down the storage hierarchy.

We propose CryoDrill, an NDP framework, which pushes parts of the computation of a data analysis workflow down the storage hierarchy to enable processing close to the data while minimizing wasteful data movements up the storage hierarchy. CryoDrill specifically targets complex data analysis tasks on large amounts of scientific data residing in cold storage devices, such as archival disks, massive-array-of-idle-disks systems, and robotic tape libraries. We plan to use in-storage processing resources by extending storage controllers to run simple computation tasks, e.g., filtering, data tiling and tile selection, and aggregation, directly within the storage device or exploit near-storage processing capabilities through FPGAs.

## Job Offerings
Are you a student looking for BSc/MSc thesis projects? Contact [me](mailto:marcus.paradies@dlr.de) for a list of available topics on large-scale data management.

* [**Student position on large-scale data management software development**](https://www.dlr.de/dlr/jobs/desktopdefault.aspx/tabid-10596/1003_read-31787/)
* [**Researcher position on large-scale data management for data-intensive radio astronomy**](https://www.dlr.de/dlr/jobs/en/desktopdefault.aspx/tabid-10596/1003_read-33368/)

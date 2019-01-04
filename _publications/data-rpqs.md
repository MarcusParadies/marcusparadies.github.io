---
title: "Analysis of Data Structures Involved in RPQ Evaluation"
collection: publications
permalink: /publication/data-rpqs
date: 2018-08-22
venue: 'DATA'
paperurl: 'http://www.scitepress.org/DigitalLibrary/Link.aspx?doi=10.5220/0006860303340343'
---

Recommended citation: Frank Tetzel and Hannes Voigt and Marcus Paradies and Romans Kasperovics and Wolfgang Lehner. (2018). "Analysis of Data Structures Involved in RPQ Evaluation." <i>DATA'18</i>.

**Abstract.** A fundamental ingredient of declarative graph query languages are regular path queries (RPQs). They provide an expressive yet compact way to match long and complex paths in a data graph by utilizing regular expressions. In this paper, we systematically explore and analyze the design space for the data structures involved in automaton-based RPQ evaluation. We consider three fundamental data structures used during RPQ processing: adjacency lists for quick neighborhood exploration, visited data structure for cycle detection, and the representation of intermediate results. We conduct an extensive experimental evaluation on realistic graph data sets and systematically investigate various alternative data structure representations and implementation variants. We show that carefully crafted data structures which exploit the access pattern of RPQs lead to reduced peak memory consumption and evaluation time.

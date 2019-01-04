---
title: "An early look at the LDBC social network benchmark's business intelligence workload"
collection: publications
permalink: /publication/grades-ldbc_bi
date: 2018-06-22
venue: 'GRADES-NDA'
paperurl: 'https://dl.acm.org/citation.cfm?id=3210268'
authors: 'Gábor Szárnyas (Budapest University of Technology and Economics), Arnau Prat-Pérez (DAMA UPC), Alex Averbuch (Neo4j), József Marton (Budapest University of Technology and Economics), Marcus Paradies (DLR), Moritz Kaufmann (TU Munich/Tableau), Orri Erling (OpenLink Software), Peter Boncz (CWI), Vlad Haprian (Oracle Labs), János Benjamin Antal (Budapest University of Technology and Economics)'
---

**Abstract.** In this short paper, we provide an early look at the LDBC Social Network Benchmark's Business Intelligence (BI) workload which tests graph data management systems on a graph business analytics workload. Its queries involve complex aggregations and navigations (joins) that touch large data volumes, which is typical in BI workloads, yet they depend heavily on graph functionality such as connectivity tests and path finding. We outline the motivation for this new benchmark, which we derived from many interactions with the graph database industry and its users, and situate it in a scenario of social network analysis. The workload was designed by taking into account technical "chokepoints" identified by database system architects from academia and industry, which we also describe and map to the queries. We present reference implementations in openCypher, PGQL, SPARQL, and SQL, and preliminary results of SNB BI on a number of graph data management systems.

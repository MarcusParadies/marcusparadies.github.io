---
title: "Juggler: Autonomous cost optimization and performance prediction of big data applications"
collection: publications
permalink: /publication/sigmod-juggler
date: 2022-06-10
venue: 'SIGMOD'
_paperurl: 'http://cidrdb.org/cidr2022/papers/p4-damme.pdf'
tag: 'dmt,ins'
storage: 'storage'
authors: 'Hani Al-Sayeh (TU Ilmenau), Bunjamin Memishi (German Aerospace Center), Muhammad Attahir Jibril (TU Ilmenau), Marcus Paradies (German Aerospace Center), Kai-Uwe Sattler (TU Ilmenau)'
---

**Abstract.** Distributed in-memory processing frameworks accelerate iterative workloads by caching suitable datasets in memory rather than recomputing them in each iteration. Selecting appropriate datasets to cache as well as allocating a suitable cluster configuration for caching these datasets play a crucial role in achieving optimal performance. In practice, both are tedious, time-consuming tasks and are often neglected by end users, who are typically not aware of workload semantics, sizes of intermediate data, and cluster specification.

To address these problems, we present Juggler, an end-to-end framework, which autonomously selects appropriate datasets for caching and recommends a correspondingly suitable cluster configuration to end users, with the aim of achieving optimal execution time and cost. We evaluate Juggler on various iterative, real-world, machine learning applications. Compared with our baseline, Juggler reduces execution time to 25.1 % and execution cost to 58.1 %, on average, as a result of selecting suitable datasets for caching. It recommends optimal cluster configuration in 50 % of cases, whereas the recommendations in the remaining cases are near-to-optimal. Moreover, Juggler achieves an average performance prediction accuracy of 90 %.

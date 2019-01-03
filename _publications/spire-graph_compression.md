---
title: "Fast Construction of Compressed Web Graphs"
collection: publications
permalink: /publication/data-rpqs
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2017-09-06
venue: 'SPIRE'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-319-67428-5_11'
---

Recommended citation: Jan Broß, Simon Gog, Matthias Hauck, Marcus Paradies. (2017). "Fast Construction of Compressed Web Graphs." <i>SPIRE'17</i>.

**Abstract.** Several compressed graph representations were proposed in the last 15 years. Today, all these representations are highly relevant in practice since they enable to keep large-scale web and social graphs in the main memory of a single machine and consequently facilitate fast random access to nodes and edges.

While much effort was spent on finding space-efficient and fast representations, one issue was only partially addressed: developing resource-efficient construction algorithms. In this paper, we engineer the construction of regular and hybrid k2 -trees. We show that algorithms based on the Z-order sorting reduce the memory footprint significantly and at the same time are faster than previous approaches. We also engineer a parallel version, which fully utilizes all CPUs and caches. We show the practicality of the latter version by constructing partitioned hybrid k-trees for Web graphs in the scale of a billion nodes and up to 100 billion edges.
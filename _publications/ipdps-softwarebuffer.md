---
title: "Software-based Buffering of Associative Operations on Random Memory Addresses"
collection: publications
permalink: /publication/ipdps-softwarebuffer
date: 2019-08-01
venue: 'IPDPS'
authors: 'Matthias Hauck (SAP), Marcus Paradies (German Aerospace Center), Holger Fröning (University of Heidelberg)'
paperurl: 'https://www.ziti.uni-heidelberg.de/ziti/uploads/ce_group/2019-IPDPS.pdf'
---

**Abstract.** An important concept for indivisible updates inparallel computing are atomic operations. For most architectures,they also provide ordering guarantees, which in practice can hurtperformance. For associative and commutative updates, in thispaper we present software buffering techniques that overcomethe problem of ordering by combining multiple updates in atemporary buffer and by prefetching addresses before updatingthem. As a result, our buffering techniques reduce contentionand avoid unnecessary ordering constraints, in order to increasethe amount of memory parallelism. We evaluate our techniquesin different scenarios, including applications like histogram andgraph computations, and reason about the applicability forstandard systems and multi-socket systems.

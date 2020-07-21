---
title: "Masha: Sampling-Based Performance Prediction of Big Data Applications in Resource-Constrained Clusters"
collection: publications
permalink: /publication/dispa-performance_prediction
date: 2020-08-31
venue: 'DISPA'
tag: 'dmt'
topic: 'prediction'
authors: 'Hani Al-Sayeh (Ilmenau University of Technology, Bunjamin Memishi (German Aerospace Center), Marcus Paradies (German Aerospace Center), Kai-Uwe Sattler (Ilmenau University of Technology)'
---

**Abstract.** Nowadays deployment of data-intensive systems in multi-dimensional domains is achieved with insufficient knowledge regarding the data, application internals, and infrastructure requirements. In addition, the current performance prediction frameworks focus to predict the performance of data-intensive applications on mid to large-scale infrastructures, which does not seem to be always the case. We reproduced 16 applications on a small-scale cluster, and obtained concerning results from a baseline prediction framework. Consequently, we argue that neither the previous design of the experiments, nor the prediction models are sufficiently accurate at resource-constrained cluster scenarios. Therefore, we propose MASHA, a new, black-box, sampling-based approach, that is initially lead by a new design of experiments, without relying on any historical executions. This is followed by a new performance prediction model, whose main idea is that apart from the computation, the data also needs a first citizen role. Our preliminary results are promising, by means of being able to characterize complex applications, having an average prediction accuracy of 83.31% , and with a negligible overhead cost of only 2.42%. Being framework-independent, MASHA is applicable to any data-intensive distributed system.

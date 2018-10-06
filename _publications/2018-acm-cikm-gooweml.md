---
title: "A Novel Online Stacked Ensemble for Multi-label Stream Classification"
collection: publications
permalink: /publication/2018-acm-cikm-gooweml
excerpt: 'In this study, we introduce a novel online and dynamically-weighted stacked ensemble for multi-label classification, called GOOWE-ML.'
date: 2018-10-23
venue: 'ACM CIKM 2018, Turin, Italy'
paperurl: 'http://dx.doi.org/10.1145/3269206.3271774'
citation: 'Alican Büyükçakır, Hamed Bonab, and Fazli Can. 2018. A Novel Online Stacked Ensemble for Multi-Label Stream Classification. In <i>Proceedings of The 27th ACM International Conference on Information and Knowledge Management, Lingotto, Turin, Italy, 22-26 October 2018 (CIKM’2018)</i>, 10 pages.'
---

See:
[[PDF (arxiv)]](https://arxiv.org/abs/1809.09994)
[[Code]](https://github.com/abuyukcakir/gooweml)

### Abstract
As data streams become more prevalent, the necessity for online algorithms that mine this transient and dynamic data becomes clearer. Multi-label data stream classification is a supervised learning problem where each instance in the data stream is classified into one or more pre-defined sets of labels. Many methods have been proposed to tackle this problem, including but not limited to ensemble-based methods. Some of these ensemble-based methods are specifically designed to work with certain multi-label base classifiers; some others employ online bagging schemes to build their ensembles. In this study, we introduce a novel online and dynamically-weighted stacked ensemble for multi-label classification, called GOOWE-ML, that utilizes spatial modeling to assign optimal weights to its component classifiers. Our model can be used with any existing incremental multi-label classification algorithm as its base classifier. We conduct experiments with 4 GOOWE-ML-based multi-label ensembles and 7 baseline models on 7 real-world datasets from diverse areas of interest. Our experiments show that GOOWE-ML ensembles yield consistently better results in terms of predictive performance in almost all of the datasets, with respect to the other prominent ensemble models.

---
title: "{DART: Dropouts meet Multiple Additive Regression Trees}"
abstract: MART, an ensemble model of boosted regression trees, is known to deliver
  high prediction accuracy for diverse tasks, and is widely used in practice. However,
  it suffers an issue which we call over-specialization, wherein trees added at later
  iterations tend to impact the prediction of only a few instances, and make negligible
  contribution towards the remaining instances. This negatively affects the performance
  of the model on unseen data, and also makes the model over-sensitive to the contributions
  of the few, initially added tress. We show that the commonly used tool to address
  this issue, that of shrinkage, alleviates the problem only to a certain extent and
  the fundamental issue of over-specialization still remains.   In this work, we explore
  a different approach to address the problem, that of employing dropouts, a tool
  that has been recently proposed in the context of learning deep neural networks.
  We propose a novel way of employing dropouts to tackle the issue of over-specialization
  in MART, resulting in the DART algorithm. We evaluate DART on ranking, regression
  and classification tasks, using large scale, publicly available datasets, and show
  that DART outperforms MART in each of the tasks, with a significant margin.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: korlakaivinayak15
month: 0
firstpage: 489
lastpage: 497
page: 489-497
sections: 
author:
- given: Rashmi
  family: Korlakai Vinayak
- given: Ran
  family: Gilad-Bachrach
date: 2015-02-21
address: San Diego, California, USA
publisher: PMLR
container-title: Proceedings of the Eighteenth International Conference on Artificial
  Intelligence and Statistics
volume: '38'
genre: inproceedings
issued:
  date-parts:
  - 2015
  - 2
  - 21
pdf: http://proceedings.mlr.press/v38/korlakaivinayak15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

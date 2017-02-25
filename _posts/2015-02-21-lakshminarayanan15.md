---
supplementary: Supplementary:lakshminarayanan15-supp.pdf
title: Particle Gibbs for Bayesian Additive Regression Trees
abstract: Additive regression trees are flexible non-parametric models and popular
  off-the-shelf tools for real-world non-linear regression. In application domains,
  such as bioinformatics, where there is also demand for probabilistic predictions
  with measures of uncertainty, the Bayesian additive regression trees (BART) model,
  introduced by Chipman et al. (2010), is increasingly popular. As data sets have
  grown in size, however, the standard Metropolis–Hastings algorithms used to per-
  form inference in BART are proving inadequate. In particular, these Markov chains
  make local changes to the trees and suffer from slow mixing when the data are high-
  dimensional or the best-fitting trees are more than a few layers deep. We present
  a novel sampler for BART based on the Particle Gibbs (PG) algorithm (Andrieu et
  al., 2010) and a top-down particle filtering algorithm for Bayesian decision trees
  (Lakshminarayanan et al., 2013). Rather than making local changes to individual
  trees, the PG sampler proposes a complete tree to fit the residual. Experiments
  show that the PG sampler outperforms existing samplers in many settings.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: lakshminarayanan15
month: 0
tex_title: "{Particle Gibbs for Bayesian Additive Regression Trees}"
firstpage: 553
lastpage: 561
page: 553-561
sections: 
author:
- given: Balaji
  family: Lakshminarayanan
- given: Daniel
  family: Roy
- given: Yee Whye
  family: Teh
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
pdf: http://proceedings.mlr.press/v38/lakshminarayanan15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

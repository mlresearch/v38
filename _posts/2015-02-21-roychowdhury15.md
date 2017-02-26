---
supplementary: http://proceedings.mlr.press/v38/roychowdhury15-supp.pdf
title: Gamma Processes, Stick-Breaking, and Variational Inference
abstract: While most Bayesian nonparametric models in machine learning have focused
  on the Dirichlet process, the beta process, or their variants, the gamma process
  has recently emerged as a useful nonparametric prior in its own right. Current inference
  schemes for models involving the gamma process are restricted to MCMC-based methods,
  which limits their scalability. In this paper, we present a variational inference
  framework for models involving gamma process priors. Our approach is based on a
  novel stick-breaking constructive definition of the gamma process. We prove correctness
  of this stick-breaking process by using the characterization of the gamma process
  as a completely random measure (CRM), and we explicitly derive the rate measure
  of our construction using Poisson process machinery. We also derive error bounds
  on the truncation of the infinite process required for variational inference, similar
  to the truncation analyses for other nonparametric models based on the Dirichlet
  and beta processes. Our representation is then used to derive a variational inference
  algorithm for a particular Bayesian nonparametric latent structure formulation known
  as the infinite  Gamma-Poisson model, where the latent variables are drawn from
  a gamma process prior with Poisson likelihoods. Finally, we present results for
  our algorithm on non-negative matrix factorization tasks on document corpora, and
  show that we compare favorably to both sampling-based techniques and variational
  approaches based on beta-Bernoulli priors, as well as a direct DP-based construction
  of the gamma process.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: roychowdhury15
month: 0
tex_title: "{Gamma Processes, Stick-Breaking, and Variational Inference}"
firstpage: 800
lastpage: 808
page: 800-808
order: 800
cycles: false
author:
- given: Anirban
  family: Roychowdhury
- given: Brian
  family: Kulis
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
pdf: http://proceedings.mlr.press/v38/roychowdhury15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

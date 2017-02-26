---
supplementary: http://proceedings.mlr.press/v38/lacoste-julien15-supp.pdf
title: 'Sequential Kernel Herding: Frank-Wolfe Optimization for Particle Filtering'
abstract: Recently, the Frank-Wolfe optimization algorithm was suggested as a procedure
  to obtain adaptive quadrature rules for integrals of functions in a reproducing
  kernel Hilbert space (RKHS) with a potentially faster rate of convergence than Monte
  Carlo integration (and “kernel herding” was shown to be a special case of this procedure).
  In this paper, we propose to replace the random sampling step in a particle filter
  by Frank-Wolfe optimization. By optimizing the position of the particles, we can
  obtain better accuracy than random or quasi-Monte Carlo sampling. In applications
  where the evaluation of the emission probabilities is expensive (such as in robot
  localization), the additional computational cost to generate the particles through
  optimization can be justified. Experiments on standard synthetic examples as well
  as on a robot localization task indicate indeed an improvement of accuracy over
  random and quasi-Monte Carlo sampling.
layout: inproceedings
series: Proceedings of Machine Learning Research
id: lacoste-julien15
month: 0
tex_title: "{Sequential Kernel Herding: Frank-Wolfe Optimization for Particle Filtering}"
firstpage: 544
lastpage: 552
page: 544-552
order: 544
cycles: false
author:
- given: Simon
  family: Lacoste-Julien
- given: Fredrik
  family: Lindsten
- given: Francis
  family: Bach
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
pdf: http://proceedings.mlr.press/v38/lacoste-julien15.pdf
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

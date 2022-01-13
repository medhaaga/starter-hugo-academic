---
title: Software - R packages
#summary: 
#date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""
share: false
---

### multichainACF


[[GitHub]](https://github.com/medhaaga/multichainACF) [[Webpage]](https://dvats.github.io/docs/mcACF.html)


Calculates the globally-centered autcorrelation function (ACF) plots following Agarwal and Vats (2020). Given a list of multiple Markov chains, this package offers functions for ACF and CCF plots that pool information from all chains yielding more accurate estimates of the correlation. The functions differs from the base acf and ccf by allowing the users to center the chains around the global mean from all Markov chains. A different mean argument can also be specified.

### quasiNewtonMM

[[GitHub]](https://github.com/medhaaga/quasiNewtonMM)

R package that implements the acceleration scheme for slowly-convergent MM algorithms (or any monotonous fixed-point iteration method) proposed by Agarwal and Xu (2020). It finds the fixed point of MM residual function using classical Broyden's quasi-Newton (BQN) method that makes secant approximations utilizing information from the MM algorithm map.


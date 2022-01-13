---
title: Research Projects
#summary: 
tags:
- Markov chain Monte Carlo
- Importance Sampling
- MM Algorithm
- Effective sample size
- 
#date: "2016-04-27T00:00:00Z"
share: false
# Optional external URL for project (replaces project detail page).
external_link: ""

---

## A principled stopping rule for importance sampling


[[Preprint]](https://arxiv.org/abs/2108.13289) [[Code]](https://github.com/medhaaga/Importance-Sampling-Stopping-Rule)


Importance sampling (IS) is a Monte Carlo technique that relies on weighted samples, simulated from a proposal distribution, to estimate intractable integrals. The quality of the estimators improves with the number of samples. However, for achieving a desired quality of estimation, the required number of samples is unknown, and depends on the quantity of interest, the estimator, and the chosen proposal. We present a sequential stopping rule that terminates simulation when the overall variability in estimation is relatively small. The proposed methodology closely connects to the idea of an effective sample size in IS and overcomes crucial shortcomings of existing metrics, e.g., it acknowledges multivariate estimation problems. Our stopping rule retains asymptotic guarantees and provides users a clear guideline on when to stop the simulation in IS.


## Quasi-Newton Acceleration of EM and MM Algorithms via Broyden's Method

[[Code]](https://github.com/medhaaga/Quasi-Newton-accelerated-MM)
[[Software]](https://github.com/medhaaga/quasiNewtonMM)


The principle of majorization-minimization (MM) provides a general framework for eliciting effective algorithms to solve optimization problems. However, they often suffer from slow convergence, especially in large-scale and  high-dimensional data settings. This has drawn attention to  acceleration schemes designed exclusively for MM algorithms, but  many existing designs are either  problem-specific or rely on approximations and heuristics loosely inspired by the optimization literature. We propose a novel, rigorous  quasi-Newton method for accelerating any valid MM algorithm, cast as seeking a fixed point of the MM \textit{algorithm map}. The method does not require specific information or computation from the objective function or its gradient, and enjoys a limited-memory variant amenable to efficient computation in high-dimensional settings. By connecting our approach to Broyden's classical root-finding methods, we establish convergence guarantees and identify conditions for linear and super-linear convergence. These results are validated numerically and compared to peer methods in a thorough empirical study, showing that it achieves state-of-the-art performance across a diverse range of problems.


## Globally-centered autocovariances in parallel MCMC

[[Preprint]](https://arxiv.org/abs/2009.01799)
[[Code]](https://github.com/medhaaga/Replicated-Spectral-Variance-Estimator)
[[Software]](https://github.com/medhaaga/multichainACF)
[[HTML]](https://htmlpreview.github.io/?https://github.com/medhaaga/multichainACF/blob/master/mcACF.html)

Advancements in modern personal computing have made it easy to run parallel Markov chain Monte Carlo (MCMC) implementations. This is particularly useful for slow mixing Markov chains where the starting points of the chains are spread over the state-space in order to more accurately capture characteristics of the target distribution. The output from parallel chains is then summarized, visually and quantitatively, to assess the empirical mixing properties of the chains and the quality of Monte Carlo estimators. In this project, we proposed a globally-centered autocovariance estimator for multiple-chain MCMC samping that exhibits significant theoretical and empirical improvements. The impact of this improved estimator is evident in three critical output analysis applications: (1) ACF plots, (2) estimates of the Monte Carlo asymptotic covariance matrix, and (3) estimates of the effective sample size. We replace the autocovariance estimator with G-ACvF in SV estimators to obtain a globally-centered SV (G-SV) estimator and demonstrate strong consistency under weak conditions. The large sample bias and variance are also computed and shown to be significantly better.


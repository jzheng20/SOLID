---
title: "A scalable global optimization algorithm for stochastic nonlinear programs"
tags: []
authors: ['Yankai Cao', 'Victor M Zavala']
publication_types: ['article-journal']
publication: "*Journal of Global Optimization 75, 393-416*"
abstract: "We present a global optimization algorithm for two-stage stochastic nonlinear programs (NLPs). The algorithm uses a tailored reduced-space spatial branch and bound (BB) strategy to exploit the nearly decomposable structure of the problem. At each node in the BB scheme, a lower bound is constructed by relaxing the so-called non-anticipativity constraints and an upper bound is constructed by fixing the first-stage variables to the current candidate solution. A key advantage of this approach is that both lower and upper bounds can be computed by solving individual scenario subproblems. Another key property of this approach is that it only needs to perform branching on the first-stage variables to guarantee convergence (branching on the second-stage variables is performed implicitly during the computation of lower and upper bounds). Notably, convergence results for this scheme also hold for two-stage stochastic MINLPs with mixed-integer first-stage variables and continuous recourse variables. We present a serial implementation of the algorithm in Julia, that we call SNGO. The implementation is interfaced to the structured modeling language Plasmo.jl, which facilitates benchmarking and model processing. Our implementation incorporates typical features that help accelerate the BB search such as LP-based lower bounding techniques, local search-based upper bounding techniques, and relaxation-based bounds tightening techniques. These strategies require the solution of extensive forms of the stochastic program but can potentially be solved using structured interior-point solvers (when the problem is an NLP). Numerical experiments are performed for a controller tuning formulation, a parameter estimation formulation for microbial growth models, and a stochastic test set from GLOBALlib. We compare the computational results against SCIP and demonstrate that the proposed approach achieves significant speedups."
date: "2019-10-01"
url_pdf: "https://optimization-online.org/wp-content/uploads/2017/08/6164.pdf"
featured: true
projects: []
slides: ""
---

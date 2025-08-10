---
title: "Scalable Global Algorithms for Stochastic Nonlinear Programming"
tags: []
authors: ['Victor M Zavala', 'Yankai Cao']
publication_types: []
publication: "*2017 AIChE Annual Meeting*"
abstract: "Many large-scale nonlinear programs (NLPs) are block structured and weakly coupled [1,2] (i.e., the NLP is composed of block subproblems problems connected by few complicating variables). For example, a two-stage stochastic program has multiple scenarios connected by first stage variables. Problems arising from parameter estimation and machine learning can also fit in this category.
This presentation introduces a new global optimization algorithm for block structured NLPs that uses a specialized branch and bound strategy. For each node in the branch and bound scheme, a lower bound is constructed by relaxing coupling constraints between complicating variables and an upper bound is constructed by fixing the complicating variables. A key advantage of this approach is that both lower bounding and upper bounding problems can be decomposed into blocks that are solved in parallel to global and local optimality, respectively. Another key property of this approach is that, because the gap between the upper bound and lower bound converges to zero as the bounds of the coupling variables converges to zero, we only need to perform branching on the complicating variables. A similar approach has been recently proposed for stochastic MINLPs [5].
We show how the algorithm can be easily implemented in Julia and interfaced to modeling languages such as JuMP and PLASMO. Our implementation also contains typical global optimization algorithmic features such as convexification, outer approximation, feasibility-based bound tightening (FBBT), optimality-based bound tightening (OBBT), and local search. Numerical experiments are performed on a stochastic optimization formulation for controller tuning and a parameter estimation formulation for microbial community models. We compare the computational results with the commercial solver BARON [3] and with open-source solver SCIP [4], and we show that the new approach achieves significant speedups."
date: "2017-11-01"
publishDate: "2017-11-01"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&cstart=100&pagesize=100&citation_for_view=M-s3mjAAAAAJ:3s1wT3WcHBgC"
featured: false
projects: []
slides: ""
---

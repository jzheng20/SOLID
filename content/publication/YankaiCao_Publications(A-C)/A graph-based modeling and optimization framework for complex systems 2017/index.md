---
title: "A graph-based modeling and optimization framework for complex systems"
authors: ['Jordan Jalving', 'Yankai Cao', 'Victor M Zavala']
tags: []
publication_types: []
publication: "*2017 AIChE Annual Meeting*"
abstract: "This talk presents PLASMO (Platform for Scalable Modeling and Optimization), a Julia-based [1] and open-source modeling platform that facilitates the creation of complex optimization applications. A distinctive feature of PLASMO is that it uses a graph abstraction in which optimization models live over nodes that are connected through edges though coupling constraints. This abstraction enables the creation of hierarchical graph models in which a node can be a graph model itself. PLASMO also uses a virtual graph abstraction in which optimization models interact with one another on-the-fly by exchanging information. Under this virtual graph abstraction, nodes are tasks and edges are communication links.
PLASMO enables modularization of complex models, because the graph topology is independent of the node models. PLASMO also facilitates the construction of coupled heterogenous networks (e.g., supply chains and natural gas and electric networks), compartmentalizes automatic differentiation and model processing tasks, manipulates graphs to perform diverse model analysis tasks (e.g., network partitioning and aggregation) and manipulates the graph so that the model can be solved solved with standard solvers (e.g., Gurobi,Ipopt) or with structured solvers (e.g., PIPS-NLP [2] and DSP [3]). Furthermore, the virtual graph abstraction facilitates the creation of algorithms such as model predictive control [4], stochastic dual dynamic programming [5], and Lagrangian relaxation [6].
This presentation will focus on the modeling aspects of PLASMO and discusses how to use the platform to model and solve coupled infrastructure networks and multi-stage stochastic programming models. The talk will conclude with a motivating example on the centralized and decentralized control of a regional power grid and gas network [7]. We also show how to create and solve multi-stage stochastic formulations for battery models.
[1] Bezanson, J., Edelman, A., Karpinski, S. & Shah, V. B. Julia: A fresh approach to numerical computing. arXiv 1–37 (2015).
[2] N. Chiang, C. G. Petra, and V. M. Zavala. Structured nonconvex optimization of large-scale energy systems using PIPS-NLP. In Proc. of the 18th Power Systems Computation Conference (PSCC), Wroclaw, Poland, 2014.
[3] K. Kim and V. M. Zavala. Algorithmic innovations and software for the dual decomposition method applied to stochastic mixed-integer programs. Optimization Online, 2015
[4] J. B. Rawllings and D. Mayne. Model predictive control: theory and design. Nob Hill Publishing, 2009.
[5] Shapiro, A. Analysis of stochastic dual dynamic programming method. Eur. J. Oper. Res. 209, 63–72 (2011).
[6] Ruszczyński, Andrzej P. Nonlinear optimization. Vol. 13. Princeton university press, 2006.
[7] Jalving, J., Abhyankar, S., Kim, K., Hereld, M., Zavala, V. M. A Graph-Based Computational Framework for Simulation and Optimization of Coupled Infrastructure Networks. To Appear in IET Generation, Transmission & Distribution, 2016."
date: "2017-10-31"
publishDate: "2017-10-31"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&pagesize=80&citation_for_view=M-s3mjAAAAAJ:3fE2CSJIrl8C"
---

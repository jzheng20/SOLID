---
title: "Graph-Based Abstractions and Tools for the Modeling and Simulation of Cyber-Physical Systems"
tags: []
authors: ['Jordan Jalving', 'Yankai Cao', 'Victor M Zavala']
publication_types: []
publication: "*2019 AIChE Annual Meeting*"
abstract: "Complex systems are inherently cyber-physical in nature [1]. For instance, a chemical process is a physical system that is driven by decisions made by a control system, which is in turn a cyber system comprised of devices (e.g., sensors, controllers, actuators) that execute diverse computing tasks and that exchange signals and data through a communication network. Modeling and simulating the behavior of cyber-physical systems is becoming increasingly important, but capturing their interdependencies is technically challenging [2]. The behavior of a physical system is expressed mathematically in the form of an algebraic model while the behavior of a cyber system is expressed mathematically in the form of algorithms which may be executed on heterogeneous computing architectures.
This talk presents abstractions to model and simulate the dependencies that arise in cyber-physical systems. We discuss an algebraic graph abstraction that captures physical connectivity in complex optimization models and a computing graph abstraction that captures communication connectivity in computing architectures. We will show how the algebraic graph performs as a general decomposition framework for optimization problems and how it facilitates the implementation and interfacing with distributed algorithms such as ADMM [3], Nested Benders [4], Lagrangian Decomposition [5], and Parallel Interior Point methods [6]. We also show how it enables graph partitioning [7] and community detection capabilities [8] which can be used to apply decomposition algorithms to complex physical systems that consider computational load balancing aspects [9].
Finally, we discuss how the computing graph abstraction facilitates the evaluation of optimization and control algorithms and their simulation in virtual environments that involve distributed, centralized, and hierarchical computing architectures. We discuss its connections with automata theory and discrete event simulation [10] and how this permits a state-space representation. We end with an example of simulating a real-time distributed control architecture subject to delays, latency, and communication and controller failures [11]. The proposed abstractions are implemented in a Julia-based software package that we call Plasmo.jl [12]."
date: "2019-11-10"
publishDate: "2019-11-10"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&cstart=80&citation_for_view=M-s3mjAAAAAJ:ZHo1McVdvXMC"
featured: false
projects: []
slides: ""
---

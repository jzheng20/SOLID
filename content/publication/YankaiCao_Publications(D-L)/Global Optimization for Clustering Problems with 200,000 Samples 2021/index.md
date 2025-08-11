---
title: "Global Optimization for Clustering Problems with 200,000 Samples"
tags: ['Global Optimization','Clustering']
authors: ['Mingfei Shi', 'Kaixun Hua', 'Yankai Cao']
publication_types: ['paper-conference']
publication: "*2021 AIChE Annual Meeting*"
abstract: "Clustering is the prototypical unsupervised learning activity that identifies cohesive and well-differentiated groups of records in data [1]. In this paper, we focus on a fundamental target of the clustering problems that minimize the within-cluster sum-of-squared-error, which can be formulated as a Mixed Integer Second Order Cone Programming (MISOCP) problem. There are many heuristic methods proposed for solving the minimum sum-of-squares clustering (MSSC) task. For instance, the k-means clustering algorithm [2] provides a coordinated descent-based method to produce a local solution. However, due to the non-convexity of the MSSC objectives, the classic k-means algorithm is sensitive to the initialization and easy to fall under the local minimum [3].
The MSSC task is rarely investigated in the literature through deterministic optimization to find its global optimal value. One reason is that a classic global optimization algorithm based on branch and bound (BB) scheme needs to perform branching on all binary variables, and the number of binary variables increases linearly as the number of data samples. Therefore, off-the-shelf global solvers cannot solve clustering problems even with hundreds of data points. In this presentation, we proposed a tailed reduced-space BB algorithm and designed four approaches to construct lower and upper bounds at each node in the BB scheme. One key advantage of this reduced-space algorithm is that it only needs to perform branching on the centers of clusters to guarantee convergence, and the size of centers is independent of the number of data samples. Another critical property of this algorithm is that both lower bounds and upper bounds can be obtained without solving any optimization problems. These two properties enable our algorithm to be scalable to the dataset with hundreds of thousands of data points. We performed numerical experiments on both synthetic and real-world datasets and compared our proposed algorithms with the off-the-shelf global optimal solvers and classical local optimal algorithms. The results reveal a strong performance and scalability of our algorithm. For example, the parallel version of our algorithm can solve the MSSC problem to an optimality gap of 1% on a synthetic dataset of 210,000 samples (i.e., 100 times larger than the state-of-the-art method [4] in the literature), using 100 CPU cores."
date: "2021-11-09"
publishDate: "2021-11-09"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&cstart=80&citation_for_view=M-s3mjAAAAAJ:XiSMed-E-HIC"
featured: false
projects: []
slides: ""
---

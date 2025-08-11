---
title: "Global Optimal K-Center Clustering with Millions of Samples"
tags: ['Global Optimization', 'K-Center Clustering']
authors: ['Yankai Cao', 'Kaixun Hua']
publication_types: ['paper-conference']
publication: "*2022 AIChE Annual Meeting*"
abstract: "Clustering is a fundamental unsupervised machine learning task that plays a vital role in various fields of applications, such as customer grouping [1], data summarization [2], and facility location determination [3]. In this talk, we concentrate on one of the most fundamental centroid-based clustering problems called the k-center problem. Given a dataset, the K-center problem aims to select k samples from the dataset as centers of clusters that minimize the maximum within-cluster distance of the dataset [4]. Although many heuristic algorithms are developed for k-center problem, none of these algorithms can guarantee a global optimal solution.
This work provides a practical global optimization algorithm for this task based on a reduced-space spatial branch and bound scheme. This algorithm can guarantee convergence to the global optimum by only branching on the centers of clusters, which is independent of the dataset’s cardinality. In addition, a set of feasibility-based bounds tightening techniques are proposed to determine the assignment of samples, narrow down the domain of centers, and significantly accelerate the convergence. To demonstrate the capacity of this algorithm, we present computational results on 26 UCI datasets [5]. Notably, for the dataset with 4 million samples ((i.e., 1000 times larger than the state-of-the-art method [6] in the literature) and 18 features, the serial implementation of the algorithm can attain the global optimum to an optimality gap of 0.1% within 2 hours."
date: "2022-11-13"
publishDate: "2022-11-13"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&cstart=80&citation_for_view=M-s3mjAAAAAJ:p2g8aNsByqUC"
featured: false
projects: []
slides: ""
---

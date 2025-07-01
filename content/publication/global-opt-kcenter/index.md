---
title: "Global Optimization of K-Center Clustering"
authors:
- Mingfei Shi
- Kaixun Hua
- Jiayang Ren
- Yankai Cao
author_notes:
- equal contribution
- equal contribution
- 
- corresponding author
date: 2022-07-01T00:00:00Z
publishDate: 2025-06-30T00:00:00Z

publication_types: ["paper-conference"]
publication: "*International Conference on Machine Learning (ICML) 2022*"
publication_short: "ICML"

abstract: |
  This work presents a practical global optimization algorithm for the k-center clustering problem using a reduced-space branch and bound framework. The method guarantees convergence to the global optimum by branching only on the centers, making it independent of the dataset size. Bounds tightening techniques are employed to reduce the domain of centers and accelerate convergence. Computational results show that the algorithm can solve a dataset with 14 million samples and 3 features to an optimality gap of 0.1% within 2 hours, outperforming heuristic methods by reducing objective value by 30.4% on average.

summary: |
  A scalable global optimization algorithm for k-center clustering problems, solving datasets with up to 14 million samples.

url_pdf: https://proceedings.mlr.press/v162/shi22b/shi22b.pdf
featured: true

image:
  caption: 'Illustration of ball-based bounds tightening for cluster 2'
  focal_point: ""
  preview_only: false

projects: []
slides: ""

links:
- name: PMLR
  url: https://proceedings.mlr.press/v162/shi22b.html
- name: PDF
  url: https://proceedings.mlr.press/v162/shi22b/shi22b.pdf
---

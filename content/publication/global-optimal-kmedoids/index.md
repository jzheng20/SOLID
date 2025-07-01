---
title: "Global Optimal K-Medoids Clustering of One Million Samples"
authors:
- Jiayang Ren
- Kaixun Hua
- Yankai Cao
author_notes:
- equal contribution
- equal contribution
- corresponding author
date: 2024-12-01T00:00:00Z

# Date when this page is published (not paper publication date)
publishDate: 2025-06-30T00:00:00Z

publication_types: ["conference-paper"]
publication: "*NeurIPS (2024)*"
publication_short: "NeurIPS"

abstract: |
  We study the deterministic global optimization of the K-Medoids clustering problem. This work proposes a branch and bound (BB) scheme, in which a tailored Lagrangian relaxation method proposed in the 1970s is used to provide a lower bound at each BB node. The lower bounding method already guarantees the maximum gap at the root node. A closed-form solution to the lower bound can be derived analytically without explicitly solving any optimization problems, and its computation can be easily parallelized. Moreover, with this lower bounding method, finite convergence to the global optimal solution can be guaranteed by branching only on the regions of medoids. We also present several tailored bound tightening techniques to reduce the search space and computational cost. Extensive computational studies on 28 machine learning datasets demonstrate that our algorithm can provide a provable global optimal solution with an optimality gap of 0.1% within 4 hours on datasets with up to one million samples. Besides, our algorithm can obtain better or equal objective values than the heuristic method. A theoretical proof of global convergence for our algorithm is also presented.

summary: |
  A global optimization method for K-Medoids clustering using branch-and-bound and Lagrangian relaxation, scalable to 1 million samples with provable optimality.

url_pdf: https://openreview.net/pdf?id=SrwrRP3yfq8
featured: true

image:
  caption: 'Image credit: Authors of the paper'
  focal_point: ""
  preview_only: false

projects: []
slides: ""

links:
- name: OpenReview
  url: https://openreview.net/forum?id=SrwrRP3yfq8
- name: PDF
  url: https://openreview.net/pdf?id=SrwrRP3yfq8
---

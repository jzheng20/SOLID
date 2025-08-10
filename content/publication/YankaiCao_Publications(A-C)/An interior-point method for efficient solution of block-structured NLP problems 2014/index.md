---
title: "An interior-point method for efficient solution of block-structured NLP problems using an implicit Schur-complement decomposition"
authors: ['Jia Kang', 'Yankai Cao', 'Daniel P Word', 'Carl D Laird']
publication: "*Computers & Chemical Engineering 71, 563-573*"
abstract: "In this work, we address optimization of large-scale, nonlinear, block-structured problems with a significant number of coupling variables. Solving these problems using interior-point methods requires the solution of a linear system that has a block-angular structure at each iteration. Parallel solution is possible using a Schur-complement decomposition. In an explicit Schur-complement decomposition, the computational cost of forming and factorizing the Schur-complement is prohibitive for problems with many coupling variables. In this paper, we show that this bottleneck can be overcome by solving the Schur-complement equations implicitly, using a quasi-Newton preconditioned conjugate gradient method. This new algorithm avoids explicit formation and factorization of the Schur-complement. The computational efficiency of this algorithm is compared with the serial full-space approach, and the serial and parallel explicit Schur-complement approach. These results show that the PCG Schur-complement approach dramatically reduces the computational cost for problems with many coupling variables."
date: "2014-12-04"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&pagesize=80&citation_for_view=M-s3mjAAAAAJ:u5HHmVD_uO8C"
featured: false
projects: []
slides: ""
---
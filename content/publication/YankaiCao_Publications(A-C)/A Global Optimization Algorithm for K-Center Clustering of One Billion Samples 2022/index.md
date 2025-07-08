---
title: "A Global Optimization Algorithm for K-Center Clustering of One Billion Samples"
tags: ["global optimization", "K-center clustering", "branch and bound"]
authors: ['Jiayang Ren', 'Fengqi You', 'Kaixun Hua', 'Chenxi Ji', 'Yankai Cao']
publication_types: ['preprint']
publication: "*arXiv preprint arXiv:2301.00061*"
abstract: "This paper presents a practical global optimization algorithm for the K-center clustering problem, which
aims to select K samples as the cluster centers to minimize the maximum within-cluster distance. This
algorithm is based on a reduced-space branch and bound scheme and guarantees convergence to the global
optimum in a finite number of steps by only branching on the regions of centers. To improve efficiency,
we have designed a two-stage decomposable lower bound, the solution of which can be derived in a closed
form. In addition, we also propose several acceleration techniques to narrow down the region of centers,
including bounds tightening, sample reduction, and parallelization. Extensive studies on synthetic and realworld datasets have demonstrated that our algorithm can solve the K-center problems to global optimal
within 4 hours for ten million samples in the serial mode and one billion samples in the parallel
mode. Moreover, compared with the state-of-the-art heuristic methods, the global optimum obtained by our
algorithm can averagely reduce the objective function by 25.8% on all the synthetic and real-world datasets."
date: "2022-12-30"
publishDate: "2022-12-30"
url_pdf: "https://arxiv.org/pdf/2301.00061"
featured: false
projects: []
slides: ""
---

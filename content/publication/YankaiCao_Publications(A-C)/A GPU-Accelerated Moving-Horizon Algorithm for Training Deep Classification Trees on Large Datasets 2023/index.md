---
title: "A GPU-Accelerated Moving-Horizon Algorithm for Training Deep Classification Trees on Large Datasets"
tags: []
authors: ['Jiayang Ren', 'Valentin Osuna-Enciso', 'Morimasa Okamoto', 'Qiangqiang Mao', 'Chaojie Ji', 'Liang Cao', 'Kaixun Hua', 'Yankai Cao']
publication_types: []
publication: "*arXiv preprint arXiv:2311.06952*"
abstract: "Decision trees are essential yet NP-complete to train, prompting the widespread use of heuristic methods such as CART, which suffers from sub-optimal performance due to its greedy nature. Recently, breakthroughs in finding optimal decision trees have emerged; however, these methods still face significant computational costs and struggle with continuous features in large-scale datasets and deep trees. To address these limitations, we introduce a moving-horizon differential evolution algorithm for classification trees with continuous features (MH-DEOCT). Our approach consists of a discrete tree decoding method that eliminates duplicated searches between adjacent samples, a GPU-accelerated implementation that significantly reduces running time, and a moving-horizon strategy that iteratively trains shallow subtrees at each node to balance the vision and optimizer capability. Comprehensive studies on 68 UCI datasets demonstrate that our approach outperforms the heuristic method CART on training and testing accuracy by an average of 3.44% and 1.71%, respectively. Moreover, these numerical studies empirically demonstrate that MH-DEOCT achieves near-optimal performance (only 0.38% and 0.06% worse than the global optimal method on training and testing, respectively), while it offers remarkable scalability for deep trees (e.g., depth=8) and large-scale datasets (e.g., ten million samples)."    
date: "2023-11-12"
publishDate: "2023-11-12"
url_pdf: "https://arxiv.org/pdf/2311.06952"
featured: false
projects: []
slides: ""
---

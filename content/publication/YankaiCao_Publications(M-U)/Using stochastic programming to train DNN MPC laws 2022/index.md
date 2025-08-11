---
title: "Using stochastic programming to train neural network approximation of nonlinear MPC laws"
tags: []
authors: ['Yun Li', 'Kaixun Hua', 'Yankai Cao']
publication_types: ['article-journal']
publication: "*Automatica 146, 110665*"
abstract: "To facilitate the real-time implementation of nonlinear model predictive control (NMPC), this paper proposes a deep learning-based NMPC scheme, in which the NMPC law is approximated via a deep neural network (DNN). To optimize the DNN controller, a novel “optimize and train” architecture is designed, where the processes of data generation and neural network training are combined together to result in a single large-scale stochastic optimization problem. Unlike the conventional “optimize then train” approach, our proposed one directly optimizes the closed-loop performance of the DNN controller over a finite horizon for a number of initial states. The important features of our proposed scheme are that it can deal with set-valued optimal MPC input, and a probabilistic guarantee of constraint satisfaction can be concluded for the closed-loop system without simulating the DNN controller. With our proposed scheme, an increased number of training scenarios leads to improved constraint satisfaction of the derived DNN controller, which is not necessarily true for the “optimize then train” approach. Statistical approaches for validating closed-loop control performance are also discussed. Furthermore, computational methods are introduced to efficiently solve the resulting stochastic optimization problem. The effectiveness of the proposed scheme is extensively illustrated with several numerical simulations. Compared with the conventional “optimize then train” approach, our proposed approach exhibits better closed-loop constraint satisfaction for all considered case studies."
date: "2022-12-01"
publishDate: "2022-12-01"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&pagesize=80&citation_for_view=M-s3mjAAAAAJ:k_IJM867U9cC"
featured: true
projects: []
slides: ""
---

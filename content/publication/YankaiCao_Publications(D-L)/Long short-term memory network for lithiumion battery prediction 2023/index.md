---
title: "Long short-term memory network with transfer learning for lithium-ion battery capacity fade and cycle life prediction"
tags: []
authors: ['Yixiu Wang', 'Jiangong Zhu', 'Liang Cao', 'Bhushan Gopaluni', 'Yankai Cao']
publication_types: ['article-journal']
publication: "*Applied Energy 350, 121660*"
abstract: "Machine Learning (ML) is a promising technique for battery health estimation and prediction. However, with more and more types of batteries entering the market, building an ML model from scratch for each new battery requires collecting a large amount of data, which is very expensive and time-consuming. This paper proposes a transfer learning approach to reduce the amount of data that needs to be recollected for a new battery. The key idea is to train an ML model for a new battery of interest (i.e., target battery) with a limited amount of data by transferring the knowledge contained in a well-studied battery (i.e., source battery) with sufficient data. We illustrate this approach using two types of batteries, i.e., the battery with Li₀.₈₆Ni₀.₈₆Co₀.₁₁Al₀.₀₃O₂ -based positive electrode (NCA battery, source battery) and the battery with Li₀.₈₄Ni₀.₈₃Co₀.₁₁Mn₀.₀₇O₂-based positive electrode (NCM battery, target battery), which have similar degradation patterns but dramatically different cycle life. Specifically, we first pre-train a long short-term memory (LSTM) network, using cycling data of 20 NCA cells at 25 °C and at 45 °C, to predict the following capacity fade based on the previous capacity sequence. Then, to make the model applicable to NCM cells, we employ the transfer learning method to retrain the model, using cycling data of only 2 NCM cells at 25 °C, and propose a two-stage approach to further improve the model performance. The proposed two-stage model can predict the cycle life of NCM cells at 45 °C using the capacities of the first 13 cycles and obtain a cycle life root-mean-squared-error (RMSE) of 25.23 cycles and a capacity trajectory RMSE of 17.80 mAh (0.51 %)."
date: "2023-11-15"
publishDate: "2023-11-15"
url_pdf: "https://scholar.google.ca/citations?view_op=view_citation&hl=zh-CN&user=M-s3mjAAAAAJ&pagesize=80&citation_for_view=M-s3mjAAAAAJ:J_g5lzvAfSwC"
featured: true
projects: []
slides: ""
---

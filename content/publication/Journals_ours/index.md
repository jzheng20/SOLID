---
title: "Using Stochastic Programming to Train Neural Network Approximation of Nonlinear MPC Laws."
authors:
- Y. Li
- K. Hua
- Y. Cao
author_notes:
- 
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article0-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Automatica (2022)*"
publication_short: ""

abstract: To facilitate the real-time implementation of nonlinear model predictive control (NMPC), this paper proposes a deep learning-based NMPC scheme, in which the NMPC law is approximated via a deep neural network (DNN). To optimize the DNN controller, a novel “optimize and train” architecture is designed, where the processes of data generation and neural network training are combined together to result in a single large-scale stochastic optimization problem. Unlike the conventional “optimize then train” approach, our proposed one directly optimizes the closed-loop performance of the DNN controller over a finite horizon for a number of initial states. The important features of our proposed scheme are that it can deal with set-valued optimal MPC input, and a probabilistic guarantee of constraint satisfaction can be concluded for the closed-loop system without simulating the DNN controller. With our proposed scheme, an increased number of training scenarios leads to improved constraint satisfaction of the derived DNN controller, which is not necessarily true for the “optimize then train” approach. Statistical approaches for validating closed-loop control performance are also discussed. Furthermore, computational methods are introduced to efficiently solve the resulting stochastic optimization problem. The effectiveness of the proposed scheme is extensively illustrated with several numerical simulations. Compared with the conventional “optimize then train” approach, our proposed approach exhibits better closed-loop constraint satisfaction for all considered case studies.

# Summary. An optional shortened abstract.
summary: To facilitate the real-time implementation of nonlinear model predictive control (NMPC), this paper proposes a deep learning-based NMPC scheme, in which the NMPC law is approximated via a deep neural network (DNN)...


# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0005109822005295?via%3Dihub

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

 
 

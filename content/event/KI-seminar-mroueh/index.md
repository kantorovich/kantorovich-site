---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Distributional Preference Alignment of Large Language Models via Optimal Transport"
event: KI Seminar
location: "ESB4133 and Online (zoom)"
registration_info: |
  Sign up for the [mailing list](https://math.us8.list-manage.com/subscribe/post?u=c9cc3beec9fa57d7299ac161c&id=845fe9abdc) to receive the connection details
speaker:
  name: Yousef Mroueh
  institution: IBM
  url: 'https://ymroueh.me/'
abstract: |
  Current LLM alignment techniques use pairwise human preferences at a sample
  level, and as such, they do not imply an alignment on the distributional
  level. We propose in this paper Alignment via Optimal Transport (AOT), a novel
  method for distributional preference alignment of LLMs. AOT aligns LLMs on
  unpaired preference data by making the reward distribution of the positive
  samples stochastically dominant in the first order on the distribution of
  negative samples. We introduce a convex relaxation of this first-order
  stochastic dominance and cast it as an optimal transport problem with a smooth
  and convex cost. Thanks to the one-dimensional nature of the resulting optimal
  transport problem and the convexity of the cost, it has a closed-form solution
  via sorting on empirical measures. We fine-tune LLMs with this AOT objective,
  which enables alignment by penalizing the violation of the stochastic
  dominance of the reward distribution of the positive samples on the reward
  distribution of the negative samples. We analyze the sample complexity of AOT
  by considering the dual of the OT problem and show that it converges at the
  parametric rate. Empirically, we show on a diverse set of alignment datasets
  and LLMs that AOT leads to state-of-the-art models in the 7B family of models
  when evaluated with Open LLM Benchmarks and AlpacaEval.  We will cover how
  these ideas extend to multivariate stochastic dominance, that is crucial for
  covering the multi-reward setting in the context of LLMs. 


    * [https://arxiv.org/pdf/2406.05882v1](https://arxiv.org/pdf/2406.05882v1)
    * [https://arxiv.org/abs/2406.06425](https://arxiv.org/abs/2406.06425)

summary: ""
authors: 
tags:
  - seminar
categories:
  - event
date: 2024-12-13T09:00:00-08:00
publishDate: 2024-12-09T09:00:00-08:00
featured: false
draft: false
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false
# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
url_video:
url_slides:
---
### Speaker Biogrpahy
Youssef Mroueh is a Principal Research Scientist in IBM Research with the
Human Centered Trustworthy AI department. He received his PhD in computer
science in February 2015 from MIT, CSAIL, where he was advised by Professor
Tomaso Poggio. In 2011, he obtained his engineering diploma from Ecole
Polytechnique Paris France, and a Master of Science in Applied Mathematics from
Ecole des Mines de Paris. He is interested in Optimal transport, trustworthy ML,
LLMs, Statistical Learning Theory, scientific ML , and AI for social good. 

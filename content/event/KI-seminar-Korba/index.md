---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Wasserstein gradient flows for machine learning"
event: KI Seminar
location: "Online (zoom)"
registration_info: |
  Sign up for the [mailing list](https://math.us8.list-manage.com/subscribe/post?u=c9cc3beec9fa57d7299ac161c&id=845fe9abdc) to receive the connection details
speaker:
  name: Anna Korba
  institution: ENSAE/CREST
  url: https://akorba.github.io/
abstract: |
   An important problem in machine learning and computational statistics is to
   sample from an intractable target distribution, e.g. to  sample or compute
   functionals (expectations, normalizing constants) of the target distribution.
   This sampling problem can be cast as the optimization of a dissimilarity
   functional, seen as a loss, over the space of probability measures. In
   particular, one can leverage the geometry of Optimal transport and consider
   Wasserstein gradient flows for the loss functional, that find continuous path
   of probability distributions decreasing this loss. Different algorithms to
   approximate the target distribution result from the choice of the loss, a
   time and space discretization; and results in practice to the simulation of
   interacting particle systems. Motivated in particular by two machine learning
   applications, namely bayesian inference and optimization of shallow neural
   networks, we will present recent convergence results obtained for algorithms
   derived from Wasserstein gradient flows.

summary:
authors:
tags: ['']
categories: ['event']
date: 2022-03-17T10:00:00-07:00
publishDate: 2022-03-04T00:00:00-08:00
lastmod: 2022-03-04T00:00:00-08:00
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
#url_video: https://mathtube.org/lecture/video/searching-most-likely-evolution
---

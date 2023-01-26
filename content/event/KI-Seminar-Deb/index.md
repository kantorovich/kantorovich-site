---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Effect of Dependence on the Convergence of Empirical Wasserstein Distance"
event: KI Seminar
location: "Online (zoom)"
registration_info: |
  Sign up for the [mailing list](https://math.us8.list-manage.com/subscribe/post?u=c9cc3beec9fa57d7299ac161c&id=845fe9abdc) to receive the connection details
speaker:
  name: Nabarun Deb
  institution: KI Postdoc, University of British Columbia
  url: https://nabarund.github.io/
abstract: |
  The Wasserstein distance is a powerful tool in modern
  machine learning to metrize the space of probability distributions in a way
  that takes into account the geometry of the domain.
  Therefore, a lot of attention has been devoted in the literature to
  understanding rates of convergence for Wasserstein distances based on i.i.d
  data. However, often in machine learning applications, especially in
  reinforcement learning, object tracking, performative prediction, and other
  online learning problems, observations are received sequentially, rendering
  some inherent temporal dependence. Motivated by this observation, we
  attempt to understand the problem of estimating Wasserstein distances using
  the natural plug-in estimator based on stationary beta-mixing sequences, a
  widely used assumption in the study of dependent processes. Our rates of
  convergence results are applicable under both short and long-range
  dependence. As expected, under short-range dependence, the rates match
  those observed in the i.i.d. case. Interestingly, however, even under
  long-range dependence, we can show that the rates can match those in the
  i.i.d. case provided the (intrinsic) dimension is large enough. Our
  analysis establishes a non-trivial trade-off between the degree of
  dependence and the complexity of certain function classes on the domain.
  The key technique in our proofs is a blend of the big-block-small-block
  method coupled with Berbee’s lemma and chaining arguments for suprema of
  empirical processes.

summary:
authors:

tags:
  - seminar
categories:
  - event
date: 2022-09-29T10:00:00-07:00
publishDate: 2022-09-21T00:00:00-07:00
lastmod: 2022-09-21T00:00:00-07:00
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
url_video: https://mathtube.org/lecture/video/effect-dependence-convergence-empirical-wasserstein-distance
url_slides: Kantorovich-Initiative-Nabarun-Slides.pdf
---

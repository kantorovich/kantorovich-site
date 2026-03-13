---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Distributional Balancing for Causal Inference: A Unified Framework via Characteristic Function Distance"
event: KI Seminar
location: "UBC - ESB4192 / Zoom"
registration_info: |
  Sign up for the [mailing list](https://mailchi.mp/b0bac0af0ff3/ki-mailing-list) to receive the connection details
speaker:
  name: Chan Park
  institution: UUIC
  url: 'https://www.chanpark.net/'
abstract: |
  Weighting methods are essential tools for estimating causal effects in
  observational studies, with the goal of balancing pre-treatment covariates
  across treatment groups. Traditional approaches pursue this objective
  indirectly, for example, via inverse propensity score weighting or by matching
  a finite number of covariate moments, and therefore do not guarantee balance
  of the full joint covariate distributions. Recently, distributional balancing
  methods have emerged as robust, nonparametric alternatives that directly
  target alignment of entire covariate distributions, but they lack a unified
  framework, formal theoretical guarantees, and valid inferential procedures. We
  introduce a unified framework for nonparametric distributional balancing based
  on the characteristic function distance (CFD) and show that widely used
  discrepancy measures, including the maximum mean discrepancy and energy
  distance, arise as special cases. Our theoretical analysis establishes
  conditions under which the resulting CFD-based weighting estimator achieves
  root-N consistency. Since the standard bootstrap may fail for this estimator,
  we propose subsampling as a valid alternative for inference. We further extend
  our approach to an instrumental variable setting to address potential
  unmeasured confounding. Finally, we evaluate the performance of our method
  through simulation studies and a real-world application, where the proposed
  estimator performs well and exhibits results consistent with our theoretical
  predictions.  The paper is available at https://arxiv.org/abs/2601.15449

summary: ""
authors: 
tags:
  - seminar
categories:
  - event
date: 2026-03-17T11:00:00-07:00
publishDate: 2026-03-12T15:30:00-07:00
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
#url_slides: GillesMordant-2025-02-20.pdf
---

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/
title: "Introduction to unbalanced optimal transport and its efficient computational solutions"
event: KI Seminar
location: "Online (zoom)"
registration_info: |
  Sign up for the [mailing list](https://math.us8.list-manage.com/subscribe/post?u=c9cc3beec9fa57d7299ac161c&id=845fe9abdc) to receive the connection details
speaker:
  name: Laetitia Chapel
  institution: Institut Agro Rennes-Angers
  url: 'https://people.irisa.fr/Laetitia.Chapel/'
abstract: |
  Optimal transport operates on empirical distributions which may contain
  acquisition artifacts, such as outliers or noise, thereby hindering a robust
  calculation of the OT map. Additionally, it necessitates equal mass between
  the two distributions, which can be overly restrictive in certain machine
  learning or computer vision applications where distributions may have
  arbitrary masses, or when only a fraction of the total mass needs to be
  transported. Unbalanced Optimal Transport addresses the issue of rebalancing
  or removing some mass from the problem by relaxing the marginal conditions.
  Consequently, it is often considered to be more robust, to some extent,
  against these artifacts compared to its standard balanced counterpart. In this
  presentation, I will review several divergences for relaxing the marginals,
  ranging from \emph{vertical} divergences like the Kullback-Leibler or the
  L2-norm, which allow for the removal of some mass, to \emph{horizontal} ones,
  enabling a more robust formulation by redistributing the mass between the
  source and target distributions. Additionally, I will discuss efficient
  algorithms that do not necessitate additional regularization on the OT plan.


summary: ""
authors: 
tags:
  - seminar
categories:
  - event
date: 2024-05-23T10:00:00-07:00
publishDate: 2024-03-23T10:00:00-07:00
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
### Speaker Biography
Laetitia Chapel is a full professor in computer science at Institut Agro
Rennes-Angers. Her research takes place within the OBELIX team of IRISA, a mixed
research unit in computer science, signal and image processing, and robotics. Her
main research topic is machine learning with a particular focus on structured
data (such as time series, graphs, hierarchical representations) and with
applications in remote sensing. She defended her HDR ("habilitation à diriger des
recherches") in 2022.

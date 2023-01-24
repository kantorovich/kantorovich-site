---
title: "IFML+KI retreat 2023"
event: "IFML+KI retreat 2023"
subtitle: ""
location: "Zillow Commons, 4th floor, [Gates Center](https://goo.gl/maps/qYR5pYtDso7KgYJN9)"

summary: |
    The second Kantorovich Initiative Retreat will take place on Thursday February 2nd, 2023 in Zillow Commons, 4th floor, [Gates Center](https://goo.gl/maps/qYR5pYtDso7KgYJN9). This is in collaboration with UW Institute for Foundations in Machine Learning (IFML). 
    
    KI retreats are local one day conferences where KI members and their research groups get together to socialize and discuss potential collaborations.  

authors: ["soumik"]

tags: ['event']
categories: ['retreat']

date: 2023-02-02T09:30:00-08:00
date_end: 2023-02-02T18:10:00-08:00
all_day: false

publishDate: 2023-01-10T10:00:00-08:00
lastmod: 2023-01-10T10:00:00-08:00

featured: true
draft: false

# image:
#   caption: "KI Retreat - group photo"
#   focal_point: ""
#   uri: "group_photo.jpg"
#   preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects: ["pihot"]
---

## Organizers
  * Soumik Pal
  * Sewoong Oh

## Schedule
  * **9:30  - 10:30**: Kevin Jamieson + Q/A 
  * **10:30 - 11:30**: Geoff Schiebinger + Q/A
  * **11:30 - 12:30**: **Keynote**: [Andrea
    Montanari](#overparametrization-in-machine-learning-insights-from-linear-models)
  * **12:30 - 2:30**: _Lunch provided (Zillow Commons)_ (120 min)
  * **2:30 - 3:20**: Jon Hayase + Q/A
  * **3:25 - 4:15**: Raghav Somani and [Raghav
    Tripathi](#scaling-limit-of-sgd-over-large-networks) + Q/A
  * **4:20 - 5:10**: [Becca
    Bonham-Carter](#developmental-trajectory-inference-in-the-presence-of-a-growth-induced-bias-in-clonal-data) + Q/A
  * **5:10 - 6:10**: _Beer and wine (Zillow Commons)_ (60 min)


## Speakers


  * [Andrea Montanari](#overparametrization-in-machine-learning-insights-from-linear-models), Stanford (Keynote)
  * Kevin Jamieson, UW+IFML (Senior talk)
  * Raghav Somani & [Raghav Tripathi](#scaling-limit-of-sgd-over-large-networks), UW+IFML+KI (Junior talk)
  * Jon Hayase, UW+IFML (Junior talk)
  * Geoff Schiebinger, UBC+KI (Senior talk)
  * [Becca
    Bonham-Carter](#developmental-trajectory-inference-in-the-presence-of-a-growth-induced-bias-in-clonal-data),
    UBC (now at Mission Control Space Services)+KI (Junior talk)


## Abstracts

{{< abstract
  title="Overparametrization in machine learning: insights from linear models"
  author="Andrea Montanari"
  affiliation="Stanford"
>}}
Deep learning models are often trained in a regime that is forbidden by
classical statistical learning theory.  The model complexity can be larger than
the sample size and the train error does not concentrate around the test error.
In fact, the model complexity can be so large that the network interpolates
noisy training data. Despite this, it behaves well on fresh test  data, a
phenomenon that has been dubbed `benign overfitting.'
I will review recent progress towards a precise quantitative understanding of
this phenomenon in linear models and kernel regression. In particular, I will
present a recent characterization of ridge regression in Hilbert spaces which
provides a unified understanding on several earlier results.  [Based on joint
work with Chen Cheng]
{{< /abstract >}}

{{< abstract
  title="Developmental trajectory inference in the presence of a growth-induced bias in clonal data"
  author="Becca Bonham-Carder"
  affiliation="UBC (now at Mission Control Space Services) + KI"
>}}
Developmental trajectory inference is the task of estimating the paths followed
by cells over time as they develop (divide, die and differentiate) in a
biological population. In this work we consider the problem of inferring
developmental trajectories at single-cell resolution from time courses of
dynamic populations which contain observations of cell developmental state and
shared ancestry through lineage tracing with DNA barcodes. A group of cells
sharing a common barcode/ancestor are referred to as a clone.
We identify and explore a statistical phenomenon that may emerge in this
inference setting, namely how the relative growth rates of cells influence the
probability that they will be sampled in clones observed across multiple time
points. We consider how this sampling bias affects state-of-the-art methods for
this inference problem, including optimal transport approaches, and how one
might design methods that are robust to this bias.
{{< /abstract >}}


{{< abstract
  title="Scaling limit of SGD over large networks"
  author="Raghav Tripathi"
  affiliation="UW+IFML+KI"
>}}
Wasserstein gradient flows often arise from mean-field interactions of
exchangeable particles. In many interesting applications however, the
“particles” are edge weights in a graph whose vertex labels are exchangeable but
not the edges themselves. We investigate the optimization of functions over this
class of symmetries. Popular applications include training of large
computational graphs like (Deep) Neural Networks. We show that discrete noisy
stochastic optimization algorithms over finite graphs have a well-defined
analytical scaling limit as the size of the network grows to infinity. The
limiting space is that of graphons, a notion introduced by Lovász and Szegedy to
describe limits of dense graph sequences. The limiting curves are given by a
novel notion of McKean-Vlasov equation on graphons and a propagation of chaos
phenomenon can be observed to hold. In the asymptotically zero-noise case, the
limit is a gradient flow on the metric space of graphons.
{{< /abstract >}}


## Sponsors

<div class="row">
  <div class="col d-flex align-items-center justify-content-center">
    <a href="https://ifml.institute" target="_blank">
      <img class="tight" src="IFML-logo.svg">
    </a>
  </div>
  <div class="col d-flex align-items-center justify-content-center">
    <a href="/">
    <img style="width:60%" class="tight" src="/img/avatar.png">
    </a>
  </div>
</div>
<div class="row mt-4">
  <div class="col d-flex align-items-center justify-content-center">
    <span class="caption"><a
    href="https://www.ifml.institute/" target="_blank">IFML</a></span>
  </div>
  <div class="col d-flex align-items-center justify-content-center">
  <span class="caption"><a href="/">Kantorovich Initiative</a></span>
  </div>
</div>
{{< pihotCRG >}}

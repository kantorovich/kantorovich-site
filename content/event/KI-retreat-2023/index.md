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
categories: ['event','retreat']

date: 2023-02-02T09:30:00-08:00
date_end: 2023-02-02T18:10:00-08:00
all_day: false

publishDate: 2023-01-10T10:00:00-08:00
lastmod: 2023-01-10T10:00:00-08:00

featured: true
draft: false

image:
  caption: "KI Retreat - group photo"
  focal_point: ""
  uri: "retreat_2023.jpg"
  preview_only: false

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
  * **9:30  - 10:30**: [Kevin Jamieson](#towards-instance-optimal-algorithms-for-reinforcement-learning) + Q/A 
  * **10:30 - 11:30**: [Geoff Schiebinger](#towards-a-mathematical-theory-of-development) + Q/A
  * **11:30 - 12:30**: **Keynote**: [Andrea
    Montanari](#overparametrization-in-machine-learning-insights-from-linear-models)
  * **12:30 - 2:30**: _Lunch provided (Zillow Commons)_ (120 min)
  * **2:30 - 3:20**: [Jon Hayase](#git-re-basin-merging-models-modulo-permutation-symmetries) + Q/A
  * **3:25 - 4:15**: Raghav Somani and [Raghav
    Tripathi](#scaling-limit-of-sgd-over-large-networks) + Q/A
  * **4:20 - 5:10**: [Becca
    Bonham-Carter](#developmental-trajectory-inference-in-the-presence-of-a-growth-induced-bias-in-clonal-data) + Q/A
  * **5:10 - 6:10**: _Beer and wine (Zillow Commons)_ (60 min)


## Speakers


  * [Andrea Montanari](#overparametrization-in-machine-learning-insights-from-linear-models), Stanford (Keynote)
  * [Kevin Jamieson](#towards-instance-optimal-algorithms-for-reinforcement-learning), UW+IFML (Senior talk)
  * [Geoff Schiebinger](#towards-a-mathematical-theory-of-development), UBC+KI (Senior talk)
  * [Jon Hayase](#git-re-basin-merging-models-modulo-permutation-symmetries), UW+IFML (Junior talk)
  * Raghav Somani & [Raghav Tripathi](#scaling-limit-of-sgd-over-large-networks), UW+IFML+KI (Junior talk)
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
  title="Towards Instance-Optimal Algorithms for Reinforcement Learning"
  author="Kevin Jamieson"
  affiliation="UW + IFML"
>}}
The theory of reinforcement learning has focused on two fundamental problems: achieving low regret, and identifying epsilon-optimal policies. While in multi-armed bandits there exists a single algorithm that is instance-optimal for both, I will show in this talk that for tabular MDPs this is no longer possible—there exists a fundamental tradeoff between achieving low regret and identifying an epsilon-optimal policy at the instance-optimal rate. That is, popular algorithms that exploit optimism cannot be instance optimal. I will then present an algorithm that achieves the best known instance-dependent sample complexity for PAC tabular reinforcement learning which explicitly accounts for the sub-optimality gaps and attainable state visitation distributions in the underlying MDP. I will then discuss our recent work in the more general linear MDP setting where we have proposed an algorithm that is qualitatively very different but nevertheless achieves an instance-dependent sample complexity.
{{< /abstract >}}


{{< abstract
  title="Towards a Mathematical Theory of Development"
  author="Geoff Schiebinger"
  affiliation="UBC + KI"
>}}
This talk introduces a mathematical theory of developmental biology, based on optimal transport. While, in principle, organisms are made of molecules whose motions are described by the Schödinger equation, there are simply too many molecules for this to be useful. Optimal transport (OT) provides a set of equations that describe development at the level of cells. We leverage OT to analyze single-cell RNA-sequencing datasets and shed light on questions like: How does a stem cell transform into a muscle cell, a skin cell, or a neuron? How can we reprogram a skin cell into a stem cell?
{{< /abstract >}}



{{< abstract
  title="Git Re Basin Merging Models modulo Permutation Symmetries"
  author="Jon Hayase"
  affiliation="UW + IFML"
>}}
The success of deep learning is due in large part to our ability to solve certain massive non-convex optimization problems with relative ease. Though non-convex optimization is NP-hard, simple algorithms -- often variants of stochastic gradient descent -- exhibit surprising effectiveness in fitting large neural networks in practice. We argue that neural network loss landscapes contain (nearly) a single basin after accounting for all possible permutation symmetries of hidden units a la Entezari et al. (2021). We introduce three algorithms to permute the units of one model to bring them into alignment with a reference model in order to merge the two models in weight space. This transformation produces a functionally equivalent set of weights that lie in an approximately convex basin near the reference model. Experimentally, we demonstrate the single basin phenomenon across a variety of model architectures and datasets, including the first (to our knowledge) demonstration of zero-barrier linear mode connectivity between independently trained ResNet models on CIFAR-10 and CIFAR-100. Additionally, we investigate intriguing phenomena relating model width and training time to mode connectivity. Finally, we discuss shortcomings of the linear mode connectivity hypothesis, including a counterexample to the single basin theory.
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

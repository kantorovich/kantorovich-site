---
title: "KI retreat 2022"
event: "KI retreat 2022"
subtitle: ""
location: "Paccar Hall, University of Washington, Seattle"

summary: |
    The Kantorovich Initiative Retreat will take place on Friday March 18th, in
    Paccar Hall, room 291.

authors: ["soumik"]

tags: ['event']
categories: ['event']

date: 2022-03-18T10:00:00-07:00
date_end: 2022-03-18T17:00:00-07:00
all_day: false

publishDate: 2022-03-18T10:00:00-07:00
lastmod: 2022-03-18T10:00:00-07:00

featured: true
draft: false

image:
  caption: "KI Retreat - group photo"
  focal_point: ""
  uri: "group_photo.jpg"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects: ["pihot"]
---

## Schedule
  * **10:00** - Room opens. 
  * **10:05 - 10:50**: Jingwei Hu, UW Applied Math {{< slides Hu.pdf >}}
  * **10:55 - 11:40**: Amir Taghvei, UW Aeronautics and Astronautics
    {{< slides Amir-Taghvaei.pdf >}}
  * **11:45 - 12:30** : Nabarun Deb, incoming KI postdoc, Columbia University 
  * **12:30 - 2:30**: Lunch Break
  * **2:30 - 3:20**: Raghav Somani, UW CSE, and Raghav Tripathi, UW Math
    {{< slides Somani-Tripathi.pdf >}}
  * **3:25 - 3:55**: Lang Liu, UW Stat {{< slides Liu.pdf >}}
  * **4:00 - 4:30**: Hyeonseok Park, UW Econ {{< slides Hyeonseok-Park.pdf >}}
  * **4:30 - 5:00**: Nick Irons, UW Stat {{< slides Irons.pdf >}}



## Abstracts

{{< abstract
  title="Particle method for the Landau Equation - A gradient flow perspective"
  author="Jingwei Hu"
  affiliation="UW, USA"
  slides="Hu.pdf"
>}}
The Landau equation is an important partial differential equation in kinetic
theory. It describes the charged particle collisions and can be formally derived
as a limit of the Boltzmann equation when all collisions become grazing. In this
work, we propose a new perspective of the Landau equation inspired by its
analogy with the heat equation and the Wasserstein-2 gradient flow of the
Boltzmann entropy. Based on this formulation, we develop a deterministic
particle method for the Landau equation which preserves important physical
properties such as conservation and entropy decay. Finally, we discuss some
ongoing work to integrate the proposed method to the popular Particle-In-Cell
method in solving the Vlasov-Landau equation in plasma physics.
{{< /abstract >}}


{{< abstract
  title="Variational Wasserstein gradient flow"
  author="Amir Taghvei"
  affiliation="UW, USA"
  slides="Amir-Taghvaei.pdf"
>}}
Wasserstein gradient flow has emerged as a promising approach to solve
optimization problems over the space of probability distributions. A recent
trend is to use the well-known JKO scheme in combination with input convex
neural networks to numerically implement the proximal step. The most challenging
step, in this setup, is to evaluate functions involving density explicitly, such
as entropy, in terms of samples. In this talk, I discuss our approach to solve
this problem that builds on the recent works with a slight but crucial
difference: we propose to utilize a variational formulation of the objective
function formulated as maximization over a parametric class of functions.
Theoretically, the proposed variational formulation allows the construction of
gradient flows directly for empirical distributions with a well-defined and
meaningful objective function. Computationally, this approach replaces the
computationally expensive step in existing methods, to handle objective
functions involving density, with inner loop updates that only require a small
batch of samples and scale well with the dimension. The performance and
scalability of the proposed method are illustrated with the aid of several
numerical experiments involving high-dimensional synthetic and real datasets.
{{< /abstract >}}


{{< abstract
  title="Optimal transport in statistics and Pitman effect multivariate distribution free testing"
  author="Nabarun Deb"
  affiliation="Columbia University, USA"
>}}
In recent years, the problem of optimal transport (see e.g., Villani (2003)) has
received significant attention in statistics and machine learning due to its
powerful geometric properties. In this talk, we introduce the optimal transport
problem and present concrete applications of this theory in statistics. In
particular, we will propose a general framework for distribution-free
nonparametric testing in multi-dimensions, based on a notion of "multivariate
ranks" defined using the theory of optimal transport. We demonstrate the
applicability of this approach by constructing exactly distribution-free tests
for two classical nonparametric problems: (i) testing for the equality of two
multivariate distributions, and (ii) testing for mutual independence between
two random vectors. We investigate the consistency and asymptotic
distributions of these tests, both under the null and local contiguous
alternatives. We further study their local power and asymptotic (Pitman)
efficiency, and show that a subclass of these tests achieve attractive
efficiency lower bounds that mimic the remarkable efficiency results of
Hodges and Lehmann (1956) and Chernoff and Savage (1958). To the best of our
knowledge, these are the first collection of multivariate exactly
distribution-free tests that provably achieve such attractive efficiency
lower bounds. Finally, we also study the rates of convergence of the
estimated optimal transport maps, which are of pivotal importance in
generative modeling, domain adaptation, etc. We will show that the natural
plugin estimators for these maps achieve minimax optimal rates of
convergence without any tuning parameters.
{{< /abstract >}}


{{< abstract
  title="Gradient flows on graphons"
  author="Raghav Somani and Raghav Tripathi"
  affiliation="UW, USA"
  slides="Somani-Tripathi.pdf"
>}}
Neural Networks (NN) can be modeled as large computational graphs with bounded
edge-weights and exchangeable nodes. Given a data distribution, the goal of a NN
is to minimize the risk function, which is a function over the edge-weights of
the network. This is typically achieved by using Euclidean gradient descent
algorithms. For single hidden layer NNs, this optimization procedure can be
viewed as the Wasserstein gradient flow over probability measures as the size of
such networks grows to infinity. We observe that large graphs like multi-layer
NNs converge to continuum limits called graphons as their size grows to
infinity. Motivated by this, we model the risk minimization problem of a single
hidden layer NN as a gradient flow on graphons. A large class of functions,
including homomorphism functions and scalar entropy, defined over graphons,
admit a gradient flow. We show that gradient flows on graphons can be obtained
as the scaling limit of the Euclidean gradient flows of suitable functions of
the edge-weights, as the size of the graph grows to infinity. The graphon
approach to NNs is more amenable to generalization to NNs with multiple hidden
layers.
{{< /abstract >}}

{{< abstract
  title="Entropy Regularized Optimal Transport Independence Criterion"
  author="Lang Liu"
  affiliation="UW, USA"
  slides="Liu.pdf"
>}}
We introduce an independence criterion based on entropy regularized optimal
transport. Our criterion can be used to test for independence between two
samples. We establish non-asymptotic bounds for our test statistic and study its
statistical behavior under both the null hypothesis and the alternative
hypothesis. The theoretical results involve tools from U-process theory and
optimal transport theory. We also offer a random feature type approximation for
large-scale problems, as well as a differentiable program implementation for
deep learning applications.  We present experimental results on existing
benchmarks for independence testing, illustrating the interest of the proposed
criterion to capture both linear and nonlinear dependencies in synthetic data
and real data.
{{< /abstract >}}

{{< abstract
  title="Minimum Sliced Distance Estimation in Structural Models"
  author="Hyeonseok Park"
  affiliation="UW, USA"
  slides="Hyeonseok-Park.pdf" >}}
Estimation and inference in structural models in economics and finance often
pose challenges to the classical likelihood-based method. In structural models
such as term structure models and dynamic stochastic general equilibrium models,
observable economic variables could be driven by fewer latent variables. This
causes stochastic singularity, and the maximum likelihood estimation (MLE) is
not well-defined. In econometric models with parameter-dependent supports such
as auction models, MLE is well defined, but the classical likelihood-based
inference may be invalid because the likelihood function can be discontinuous
depending on the underlying structural parameters.
 
This talk introduces a simple and robust method for the estimation and inference
in structural econometric models based on sliced distances. In contrast to MLE
and likelihood-based inference, we show that under mild regularity conditions,
our estimator is asymptotically normally distributed, leading to simple
inference regardless of the possible presence of ”stochastic singularity” such
as in the asset pricing/state-space models and parameter-dependent supports.
Furthermore, our estimator is applicable to generative models with intractable
likelihood functions but from which one can easily draw synthetic samples. 
 
This talk is based on the joint work with Prof. Yanqin Fan.
{{< /abstract >}}


{{< abstract
  title="Consistency and Convergence rates of smooth triangular flows"
  author="Nick Irons"
  affiliation="UW, USA"
  slides="Irons.pdf"
>}}
Triangular flows, also known as Knöthe-Rosenblatt measure couplings, comprise an
important building block of normalizing flow models for generative modeling and
density estimation, including popular autoregressive flow models such as
real-valued non-volume preserving transformation models (Real NVP). We present
statistical guarantees and sample complexity bounds for triangular flow
statistical models. In particular, we establish the statistical consistency and
the finite sample convergence rates of the Kullback-Leibler estimator of the
Knöthe-Rosenblatt measure coupling using tools from empirical process theory.
Our results highlight the anisotropic geometry of function classes at play in
triangular flows, shed light on optimal coordinate ordering, and lead to
statistical guarantees for Jacobian flows.
{{< /abstract >}}

{{< pihotCRG >}}

---
title: "Learning in Hybrid Active Inference Models"
collection: publications
permalink: /publication/2024-31-12-learning-in-hybrid-aif
excerpt: 'A novel hierarchical hybrid active inference agent in which a high-level discrete planner is formed from emergent descriptions discovered by a recurrent switching linear dynamical system generative model.'
date: 2024-12-1
venue: 'Communications in Computer and Information Science, vol 2193'
paperurl: ''
citation: 'Collis, P., Singh, R., Kinghorn, P.F., Buckley, C.L. (2025). Learning in Hybrid Active Inference Models. In: Buckley, C.L., et al. Active Inference. IWAI 2024. Communications in Computer and Information Science, vol 2193. Springer, Cham.'
---

An open problem in artificial intelligence is how systems can flexibly learn discrete abstractions that are useful for solving inherently continuous problems. Previous work in computational neuroscience has considered this functional integration of discrete and continuous variables during decision-making under the formalism of active inference (Friston et al., 2017; Parr & Friston, 2018). However, their focus is on the expressive physical implementation of categorical decisions and the hierarchical mixed generative model is assumed to be known. As a consequence, it is unclear how this framework might be extended to the learning of appropriate coarse-grained variables for a given task. In light of this, we present a novel hierarchical hybrid active inference agent in which a high-level discrete active inference planner sits above a low-level continuous active inference controller. We make use of recent work in recurrent switching linear dynamical systems (rSLDS) which learn meaningful discrete representations of complex continuous dynamics via piecewise linear decomposition (Linderman et al., 2016). The representations learnt by the rSLDS inform the structure of the hybrid decision-making agent and allow us to (1) lift decision-making into the discrete domain enabling us to exploit information-theoretic exploration bonuses (2) specify temporally-abstracted sub-goals in a method reminiscent of the options framework (Sutton et al., 1999) and (3) ‘cache’ the approximate solutions to low-level problems in the discrete planner. We apply our model to the sparse Continuous Mountain Car task, demonstrating fast system identification via enhanced exploration and successful planning through the delineation of abstract sub-goals.

[Download pre-print here](https://arxiv.org/pdf/2409.01066)

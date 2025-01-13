---
title: "Hybrid Recurrent Models Support Emergent Descriptions for Hierarchical Planning and Control"
collection: publications
permalink: /publication/2024-08-20-hybrid-recurrent-models
excerpt: 'A novel hierarchical hybrid active inference agent in which a high-level discrete planner is formed from emergent descriptions discovered by a recurrent switching linear dynamical system generative model.'
date: 2024-8-20
venue: 'arXiv preprint'
paperurl: ''
citation: 'Collis, P., Singh, R., Kinghorn, P.F., Buckley, C.L. (2024). Hybrid Recurrent Models Support Emergent Descriptions for Hierarchical Planning and Control. arXiv preprint.'
---

Accepted for the Foundations of Reinforcement Learning and Control (FoRLaC) Workshop at the International Conference on Machine Learning (ICML) 2024

An open problem in artificial intelligence is how systems can flexibly learn discrete abstractions that are useful for solving inherently continuous problems. Previous work has demonstrated that a class of hybrid state-space model known as recurrent switching linear dynamical systems (rSLDS) discover meaningful behavioural units via the piecewise linear decomposition of complex continuous dynamics (Linderman et al., 2016). Furthermore, they model how the underlying continuous states drive these discrete mode switches. We propose that the rich representations formed by an rSLDS can provide useful abstractions for planning and control. We present a novel hierarchical model-based algorithm inspired by Active Inference in which a discrete MDP sits above a low-level linear-quadratic controller. The recurrent transition dynamics learned by the rSLDS allow us to (1) specify temporally-abstracted sub-goals in a method reminiscent of the options framework, (2) lift the exploration into discrete space allowing us to exploit information-theoretic exploration bonuses and (3) `cache' the approximate solutions to low-level problems in the discrete planner. We successfully apply our model to the sparse Continuous Mountain Car task, demonstrating fast system identification via enhanced exploration and non-trivial planning through the delineation of abstract sub-goals.

[Download pre-print here](https://arxiv.org/abs/2408.10970)

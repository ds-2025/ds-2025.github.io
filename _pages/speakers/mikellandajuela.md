---
layout: page
permalink: /speakers/mikellandajuela/
title: Mikel Landajuela
description:
nav: false
nav_order:
---

<img src="/assets/img/speakers/mikel-landajuela.jpg" class="img-fluid img-center speaker-img" alt="Iryna Gurevych">

## Deep Symbolic Optimization: Reinforcement Learning for Equation Discovery

Symbolic regression seeks concise mathematical formulas to describe scientific data, producing models that are transparent and human-interpretable. However, the space of possible symbolic expressions is combinatorially enormous, making search for optimal equations challenging. Deep Symbolic Optimization (DSO) addresses this by framing equation discovery as a sequential decision process guided by reinforcement learning.

In DSO, an autoregressive neural model generates candidate equations token by token, and each formula is scored by its fit to data. A “risk-seeking” policy keeps only the top-scoring expressions to update the model, biasing learning toward promising symbolic forms. Domain priors or constraints can further focus the search on valid or likely solutions. Furthermore, pre-trained models can be used to initialize the search, leveraging existing knowledge to jumpstart the discovery process.

By leveraging deep networks to guide combinatorial search, DSO navigates huge spaces of symbolic formulas, producing compact, interpretable models that capture data patterns. It has achieved state-of-the-art results on symbolic regression benchmarks and even won international equation-discovery competitions. Because DSO works on any discrete-sequence optimization problem, it can be applied beyond equations—for example, to discover symbolic control policies or decision-tree controllers in science and engineering. Overall, DSO shows how reinforcement learning can automate the discovery of human-readable models, aiding scientific discovery with transparent AI.

## Biography

Mikel Landajuela is a Senior Staff Scientist in Machine Learning at Lawrence Livermore National Laboratory, where he leads efforts in interpretable AI and reinforcement‑learning‑guided symbolic regression. After earning his PhD in Applied Mathematics from Université Pierre et Marie Curie and Inria in Paris, he joined LLNL, contributing award-winning research such as Deep Symbolic Optimization (DSO). DSO frames symbolic regression as a sequential decision task, using a neural generative model and risk-seeking policy gradients to discover interpretable mathematical expressions—achieving state-of-the-art results on benchmarks and winning global competitions.

Beyond symbolic regression, Mikel’s work extends DSO to hybrid discrete-continuous problems, symbolic control policies, and scientific domains such as drug discovery and antibody design. His research merges deep learning with high-performance computing to uncover transparent scientific models, from discovering physical laws to interpretable decision-making in dynamic environments.

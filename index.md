---
layout: page
title: Pierre Bonami
---

<img src="{{ site.baseurl }}/assets/profile.jpg" alt="Pierre Bonami" style="float:right;margin:0 0 1em 2em;border-radius:50%;width:140px;height:140px;object-fit:cover;">

I am a Principal Developer at
[Gurobi Optimization](https://www.gurobi.com) based in **Madrid, Spain**.

## Background

My career spans academia and industry, with positions at:

- **Gurobi Optimization** — Principal Developer (current)
- **IBM** — Research Scientist in the
  [CPLEX](https://www.ibm.com/products/ilog-cplex-optimization-studio) team.
- **CNRS** — Permanent Researcher at [LIF Marseille](https://www.lis-lab.fr) (now LIS).
- **[Carnegie Mellon University](https://www.cmu.edu)** — Postdoctoral research in optimization

I earned my PhD in Operations Research at [Paris 6 (LIP6)](https://www.lip6.fr), focusing on algorithms for
Mixed-Integer Nonlinear Programming.

Currently, I work on the algorithms and solvers that power
[Gurobi](https://www.gurobi.com), one of the world's leading mathematical
optimization platforms. My work spans **Mixed-Integer Programming (MIP)**,
**Mixed-Integer Nonlinear Programming (MINLP)**, **cutting-planes**, and interactions
of optimization with Machine Learning.

I am the creator and project manager of
**[Bonmin](https://coin-or.github.io/Bonmin/)** (Basic Open-source Nonlinear
Mixed INteger programming), an open-source C++ solver for convex MINLP problems,
distributed through the [COIN-OR](https://www.coin-or.org/) initiative.

## Research Interests

My research spans **Mixed-Integer Programming (MIP)**, **Mixed-Integer Nonlinear
Programming (MINLP)**, and **cutting-plane theory**. I design algorithms that
tighten LP relaxations via
[split disjunctions and wide split cuts](https://doi.org/10.1007/978-3-319-59250-3_9),
solve
[nonconvex quadratic programs via integer programming](https://doi.org/10.1137/16M107428X),
automate
[Benders decomposition inside solvers](https://doi.org/10.1007/978-3-030-45771-6_7),
and apply
[machine learning to guide algorithm selection](https://doi.org/10.1287/opre.2022.2267).
A growing focus of my work is the **interaction between optimization and machine
learning**: using ML to improve solver decisions, and conversely, embedding
trained predictors inside optimization models.

## Gurobi Machine Learning

I maintain
**[gurobi-machinelearning](https://github.com/Gurobi/gurobi-machinelearning)**,
an open-source Python package that lets you embed trained regression models —
from scikit-learn, Keras/TensorFlow, or PyTorch — directly inside a
[gurobipy](https://pypi.org/project/gurobipy/) optimization model. This makes it
possible to optimize over the input space of a learned predictor using Gurobi's
exact MIP solver, bridging the gap between machine learning and mathematical
optimization. Full documentation is available on
[ReadTheDocs](https://gurobi-optimization-gurobi-machine-learning.readthedocs-hosted.com).

## Bonmin

I created **[Bonmin](https://coin-or.github.io/Bonmin/)** (Basic Open-source
Nonlinear Mixed INteger programming), an open-source C++ solver for convex
MINLP, distributed through [COIN-OR](https://www.coin-or.org/). Bonmin is very
loosely maintained.

## Links

- 🐙 [GitHub — pobonomo](https://github.com/pobonomo)
- 🎓 [Google Scholar](https://scholar.google.com/scholar?q=Pierre+Bonami)
- 📖 [DBLP](https://dblp.org/pid/48/4147)
- 🔗 [Gurobi](https://www.gurobi.com)
- 🔬 [Gurobi Machine Learning](https://github.com/Gurobi/gurobi-machinelearning)

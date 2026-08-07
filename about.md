---
layout: page
title: About
permalink: /about/
nav_order: 2
---

# About Me

<img src="{{ site.baseurl }}/assets/profile.jpg" alt="Pierre Bonami" style="float:right;margin:0 0 1em 2em;border-radius:50%;width:140px;height:140px;object-fit:cover;">

I am **Pierre Bonami**, a Principal Developer at [Gurobi Optimization](https://www.gurobi.com) based in **Madrid, Spain**.

## Background

My career spans academia and industry, with positions at:

- **Gurobi Optimization** — Principal Developer (current)
- **IBM** — Research Scientist in teh [CPLEX](https://www.ibm.com/products/ilog-cplex-optimization-studio) team.
- **CNRS** — Permanent researcher at LIF Marseille.
- **Carnegie Mellon University** — Postdoctoral research in optimization

I earned my PhD in Operations Research at Paris 6, focusing on algorithms for Mixed-Integer Nonlinear Programming.

## Research Interests

My work focuses on the theoretical and practical aspects of **mathematical optimization**:

**Mixed-Integer Nonlinear Programming (MINLP).** I design and implement algorithms for convex MINLP, including branch-and-bound, outer approximation, and hybrid methods. This work is embodied in [Bonmin](https://coin-or.github.io/Bonmin/), the open-source solver I created, whose foundations are described in [*An Algorithmic Framework for Convex Mixed Integer Nonlinear Programs*](https://doi.org/10.1016/j.disopt.2006.10.011) (Bonami et al., 2008).

**MIP Cutting Planes.** I study cutting-plane methods — split disjunctions, wide split cuts, two-row cuts — that tighten LP relaxations of mixed-integer programs. Recent work includes [*Cutting Planes from Wide Split Disjunctions*](https://doi.org/10.1007/978-3-319-59250-3_9) (IPCO 2017) and *Cutting Planes for Binarized Network Flow Problems* (with Dash, Derkach, Lodi, 2026).

**Quadratic & Nonlinear MIP.** I develop methods for globally solving nonconvex quadratic programs via integer programming techniques, and for deciding when to linearize mixed-integer quadratic problems inside a solver. See [*Solving Quadratic Programming by Cutting Planes*](https://doi.org/10.1137/16M107428X) (*SIAM J. Optim.*, 2019) and [*A Classifier to Decide on the Linearization of MIQP in CPLEX*](https://doi.org/10.1287/opre.2022.2267) (*Operations Research*, 2022).

**Automatic Benders Decomposition.** I contributed to embedding Benders decomposition automatically inside a modern MIP solver, described in [*Implementing Automatic Benders Decomposition in a Modern MIP Solver*](https://doi.org/10.1007/978-3-030-45771-6_7) (IPCO 2020, with Salvagnin and Tramontani).

**Machine Learning for Optimization.** I explore using ML classifiers to guide algorithm-selection decisions inside solvers — from choosing whether to linearize a MIQP to predicting solver behaviour — as shown in [*Learning a Classification of MIQP Problems*](https://doi.org/10.1007/978-3-319-93031-2_43) (CPAIOR 2018).

## Bonmin

I created **[Bonmin](https://coin-or.github.io/Bonmin/)** (Basic Open-source Nonlinear Mixed INteger programming), an open-source C++ solver for convex MINLP, distributed through [COIN-OR](https://www.coin-or.org/). Bonmin is very loosely maintained.

## Gurobi Machine Learning

I contribute to **[gurobi-machinelearning](https://github.com/Gurobi/gurobi-machinelearning)**, an open-source Python package that lets you embed trained regression models — from scikit-learn, Keras/TensorFlow, or PyTorch — directly inside a [gurobipy](https://pypi.org/project/gurobipy/) optimization model. This makes it possible to optimize over the input space of a learned predictor using Gurobi's exact MIP solver, bridging the gap between machine learning and mathematical optimization. Full documentation is available on [ReadTheDocs](https://gurobi-optimization-gurobi-machine-learning.readthedocs-hosted.com).

## Links

- 🐙 [GitHub — pobonomo](https://github.com/pobonomo)
- 🎓 [Google Scholar](https://scholar.google.com/scholar?q=Pierre+Bonami)
- 📖 [DBLP](https://dblp.org/pid/48/4147)
- 🔗 [Gurobi](https://www.gurobi.com)
- 🔬 [Bonmin project](https://coin-or.github.io/Bonmin/)

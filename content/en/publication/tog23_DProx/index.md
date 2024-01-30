---
title: "∇-Prox: Differentiable Proximal Algorithm Modeling for Large-Scale Optimization"
authors:
- "Zeqiang Lai*"
- "**Kaixuan Wei***"
- Ying Fu
- Philipp Härtel
- Felix Heide
date: "2023-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "In *ACM Transactions on Graphics (TOG)*, 2023"

abstract: "Tasks across diverse application domains can be posed as large-scale optimization problems, these include graphics, vision, machine learning, imaging, health, scheduling, planning, and energy system forecasting. Independently of the application domain, proximal algorithms have emerged as a formal optimization method that successfully solves a wide array of existing problems, often exploiting problem-specific structures in the optimization. Although model-based formal optimization provides a principled approach to problem modeling with convergence guarantees, at first glance, this seems to be at odds with black-box deep learning methods. A recent line of work shows that, when combined with learning-based ingredients, model-based optimization methods are effective, interpretable, and allow for generalization to a wide spectrum of applications with little or no extra training data. However, experimenting with such hybrid approaches for different tasks by hand requires domain expertise in both proximal optimization and deep learning, which is often error-prone and time-consuming. Moreover, naively unrolling these iterative methods produces lengthy compute graphs, which when differentiated via autograd techniques results in exploding memory consumption, making batch-based training challenging. In this work, we introduce ∇-Prox, a domain-specific modeling language and compiler for large-scale optimization problems using differentiable proximal algorithms. ∇-Prox allows users to specify optimization objective functions of unknowns concisely at a high level, and intelligently compiles the problem into compute and memory-efficient differentiable solvers. One of the core features of ∇-Prox is its full differentiability, which supports hybrid model- and learning-based solvers integrating proximal optimization with neural network pipelines. Example applications of this methodology include learning-based priors and/or sample-dependent inner-loop optimization schedulers, learned with deep equilibrium learning or deep reinforcement learning. With a few lines of code, we show ∇-Prox can generate performant solvers for a range of image optimization problems, including end-to-end computational optics, image deraining, and compressive magnetic resonance imaging. We also demonstrate ∇-Prox can be used in a completely orthogonal application domain of energy system planning, an essential task in the energy crisis and the clean energy transition, where it outperforms state-of-the-art CVXPY and commercial Gurobi solvers. "

# Summary. An optional shortened abstract.
# summary: "*Preprint on arXiv:2002.09611*"
summary:  "*ACM Transactions on Graphics **(SIGGRAPH 2023)**, Los Angeles, USA*"

tags:
- Domain-specific Language
- Variational Optimization
- Computational Imaging
featured: false

links:
- name: Project Page
  url: https://light.princeton.edu/publication/delta_prox/
url_pdf: https://dl.acm.org/doi/abs/10.1145/3592144
url_code: 'https://github.com/princeton-computational-imaging/Delta-Prox'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

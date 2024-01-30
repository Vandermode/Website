---
title: "TFPnP: Tuning-free Plug-and-Play Proximal Algorithms with Applications to Inverse Imaging Problems"
authors:
- "**Kaixuan Wei**"
- Angelica Aviles-Rivero
- Jingwei Liang 
- Ying Fu
- Hua Huang
- Carola-Bibiane Sch¨onlieb
date: "2022-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "In *Journal of Machine Learning Research (JMLR)*, 2022"

abstract: "Plug-and-Play (PnP) is a non-convex optimization framework that combines proximal algorithms, for example, the alternating direction method of multipliers (ADMM), with advanced denoising priors. Over the past few years, great empirical success has been obtained by PnP algorithms, especially for the ones that integrate deep learning-based denoisers. However, a key problem of PnP approaches is the need for manual parameter tweaking which is essential to obtain high-quality results across the high discrepancy in imaging conditions and varying scene content. In this work, we present a class of tuning-free PnP proximal algorithms that can determine parameters such as denoising strength, termination time, and other optimization-specific parameters automatically. A core part of our approach is a policy network for automated parameter search which can be effectively learned via a mixture of model-free and model-based deep reinforcement learning strategies. We demonstrate, through rigorous numerical and visual experiments, that the learned policy can customize parameters to different settings, and is often more efficient and effective than existing handcrafted criteria. Moreover, we discuss several practical considerations of PnP denoisers, which together with our learned policy yield state-of-the-art results. This advanced performance is prevalent on both linear and nonlinear exemplar inverse imaging problems, and in particular shows promising results on compressed sensing MRI, sparse-view CT, single-photon imaging, and phase retrieval. "

# Summary. An optional shortened abstract.
# summary: "*Preprint on arXiv:2002.09611*"
summary: "*Journal of Machine Learning Research (**JMLR**), 2022*"  

tags:
- Reinforcement Learning
- Variational Optimization
- Computational Imaging
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://jmlr.org/papers/volume23/20-1297/20-1297.pdf
url_code: 'https://github.com/Vandermode/TFPnP'


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

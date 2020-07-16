---
title: "Tuning-free Plug-and-Play Proximal Algorithm for Inverse Imaging Problems"
authors:
- "**Kaixuan Wei**"
- Angelica Aviles-Rivero
- Jingwei Liang 
- Ying Fu
- Carola-Bibiane Schnlieb
- Hua Huang
date: "2020-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "Plug-and-play (PnP) is a non-convex framework that combines ADMM or other proximal algorithms  with advanced denoiser priors.  Recently, PnP has achieved great empirical  success, especially with the integration of deep learning-based denoisers. 
However, a key problem of PnP based approaches is that they require manual parameter tweaking. It is necessary to obtain high-quality results across the high discrepancy in terms of imaging conditions and varying scene content.
In this work, we present a tuning-free PnP proximal algorithm, which can automatically  determine the internal parameters including  the penalty parameter, the denoising strength  and the terminal time. A key part of our approach is to develop a policy network for automatic search of parameters, which can be effectively learned via mixed model-free and model-based deep reinforcement learning. 
We demonstrate, through numerical and visual experiments, that the learned policy can customize different parameters for different states, and often more efficient and effective than existing handcrafted criteria. Moreover, we discuss the practical considerations of the plugged denoisers, which together with our learned policy yield  state-of-the-art results. This is prevalent on both linear and nonlinear exemplary inverse imaging problems, and in particular, we show promising results on Compressed Sensing MRI and phase retrieval. "

# Summary. An optional shortened abstract.
# summary: "*Preprint on arXiv:2002.09611*"
summary: "*The 37th International Conference on Machine Learning **(ICML 2020)**, Vienna, Austria,* **Outstanding Paper Award, Acceptance Rate: 0.04%** "  

tags:
- Reinforcement Learning
- Variational Optimization
- Computational Imaging
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://www.researchgate.net/publication/339471639_Tuning-free_Plug-and-Play_Proximal_Algorithm_for_Inverse_Imaging_Problems
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

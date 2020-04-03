---
title: "Low-rank Bayesian Tensor Factorization for Hyperspectral Image Denoising"
authors:
- "**Kaixuan Wei**"
- Ying Fu
date: "2019-02-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-02-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Neurocomputing*"
# publication_short: ""

abstract: "In this paper, we present a low-rank Bayesian tensor factorization approach for
  hyperspectral image (HSI) denoising problem, where zero-mean white and
  homogeneous Gaussian additive noise is removed from a given HSI. The approach
  is based on two intrinsic properties underlying a HSI, i.e., the global
  correlation along spectrum (GCS) and nonlocal self-similarity across space
  (NSS). We first adaptively construct the patch-based tensor representation for
  the HSI to extract the NSS knowledge while preserving the property of GCS.
  Then, we employ the low rank property in this representation to design a
  hierarchical probabilistic model based on Bayesian tensor factorization to
  capture the inherent spatial-spectral correlation of HSI, which can be
  effectively solved 
  under the variational Bayesian framework. Furthermore, through incorporating
  these two procedures in an iterative
  manner, we build an effective HSI denoising model to recover HSI from its
  corruption. This leads to a state-of-the-art denoising performance,
  consistently surpassing recently published leading HSI denoising methods in
  terms of both comprehensive quantitative assessments and subjective visual
  quality."

# Summary. An optional shortened abstract.
summary: "*Elsevier Neurocomputing, 2019*"

tags:
- Low-level Vision
- Hyperspectral Image Processing
- Variational Inference
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.researchgate.net/publication/329150744_Low-rank_Bayesian_Tensor_Factorization_for_Hyperspectral_Image_Denoising
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

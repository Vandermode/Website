---
title: "3D Quasi-Recurrent Neural Network for Hyperspectral Image Denoising"
authors:
- "**Kaixuan Wei**"
- Ying Fu
- Hua Huang
date: "2020-02-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-16T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Neural Networks and Learning System, 2020*"
# publication_short: ""

abstract:  "In this paper, we propose an alternating directional 3D quasi-recurrent neural network for hyperspectral image (HSI) denoising, which can effectively embed the domain knowledge --- structural spatio-spectral correlation and global correlation along spectrum. Specifically, 3D convolution is utilized to extract structural spatio-spectral correlation in an HSI, while a quasi-recurrent pooling function is employed to capture the global correlation along spectrum. Moreover, alternating directional structure is introduced to eliminate the causal dependency with no additional computation cost. The proposed model is capable of modeling spatio-spectral dependency while preserving the flexibility towards HSIs with arbitrary number of bands. Extensive experiments on HSI denoising demonstrate significant improvement over state-of-the-arts under various noise settings, in terms of both restoration accuracy and computation time. Our code is available at https://github.com/Vandermode/QRNN3D."

# Summary. An optional shortened abstract.
summary: "*IEEE Transactions on Neural Networks and Learning System, 2020*"

tags:
- Low-level Vision
- Hyperspectral Image Processing
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2003.04547
url_code: 'https://github.com/Vandermode/QRNN3D'

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

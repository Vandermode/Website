---
title: "Physics-based Noise Modeling for Extreme Low-light Photography"
authors:
- "**Kaixuan Wei**"
- Ying Fu
- Yinqiang Zheng
- Jiaolong Yang
date: "2021-08-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-04T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, 2021

abstract:   Enhancing the visibility in extreme low-light environments is a challenging task. Under nearly lightless condition, existing image denoising methods could easily break down due to significantly low SNR. In this paper, we systematically study the noise statistics in the imaging pipeline of CMOS photosensors, and formulate a comprehensive noise model that can accurately characterize the real noise structures. Our novel model considers the noise sources caused by digital camera electronics which are largely overlooked by existing methods yet have significant influence on raw measurement in the dark. It provides a way to decouple the intricate noise structure into different statistical distributions with physical interpretations. Moreover, our noise model can be used to synthesize realistic training data for learning-based low-light denoising algorithms. In this regard, although promising results have been shown recently with deep convolutional neural networks, the success heavily depends on abundant noisy-clean image pairs for training, which are tremendously difficult to obtain in practice. Generalizing their trained models to images from new devices is also problematic. Extensive experiments on multiple low-light denoising datasets -- including a newly collected one in this work covering various devices -- show that a deep neural network trained with our proposed noise formation model can reach surprisingly-high accuracy. The results are on par with or sometimes even outperform training with paired real data, opening a new door to real-world extreme low-light photography. 

# Summary. An optional shortened abstract.
summary: "*IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI**), 2021*" 

tags:
- Low-level Vision
- Computational Photography
- Statistical Modeling/Inference
featured: false

links:
url_pdf: "https://arxiv.org/abs/2108.02158"
url_code: 'https://github.com/Vandermode/ELD'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: ""
---

---
title: "A Physics-based Noise Formation Model for Extreme Low-light Raw Denoising"
authors:
- "**Kaixuan Wei**"
- Ying Fu
- Jiaolong Yang
- Hua Huang
date: "2020-02-23T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-02-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2020

abstract:   Lacking rich and realistic data, learned single image denoising algorithms
  generalize poorly to real raw images that not resemble the data used for
  training. Although the problem can be alleviated by the
  heteroscedastic Gaussian noise model, the noise sources caused by digital
  camera electronics are still largely overlooked, despite their significant effect on
  raw measurement, especially under extremely low-light condition. To address
  this issue, we present a highly accurate noise formation model based on the
  characteristics of CMOS photosensors, thereby enabling us to synthesize
  realistic samples that better match the physics of image formation process.
  Given the proposed noise model, we additionally propose a
  method to calibrate the noise parameters for available modern digital
  cameras, which is simple and reproducible for any new device. We
  systematically study the generalizability of a neural network trained with
  existing schemes, by introducing a new low-light denoising dataset that covers
  many modern digital cameras from diverse brands. Extensive empirical results
  collectively show that by utilizing our proposed noise formation model, a
  network can reach the capability as if it had been trained with rich real
  data, which demonstrates the effectiveness of our noise formation model.

# Summary. An optional shortened abstract.
summary: "*The 36th IEEE Conference on Computer Vision and Pattern Recognition **(CVPR 2020)**, Seattle, USA,* **Oral Presentation, Acceptance Rate: 5%**" 

tags:
- Low-level Vision
- Computational Photography
- Statistical Modeling/Inference
featured: false

links:
- name: Talk
  url: https://www.youtube.com/watch?v=DMDKPRozdeo
url_pdf: "https://www.researchgate.net/publication/340295293_A_Physics-based_Noise_Formation_Model_for_Extreme_Low-light_Raw_Denoising"
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

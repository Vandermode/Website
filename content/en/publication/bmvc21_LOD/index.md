---
title: "Crafting Object Detection in Very Low Light"
authors:
- Yang Hong*
- "**Kaixuan Wei***"
- Linwei Chen
- Ying Fu
date: "2021-11-22:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-22T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *The British Machine Vision Conference (BMVC)*, 2021

abstract:   Over the last decade, object detection, as a leading application in computer vision, has been intensively studied, heavily engineered and widely applicable to everyday life. However, existing object detection algorithms could easily break down under very dim environments, due to significantly low signal-to-noise ratio (SNR). Prepending a low-light image enhancement step before detection, as a common practice, increases the computation cost substantially, yet still does not yield satisfactory results. In this paper, we systematically investigate object detection in very low light and identify several design principles that are essential to the low-light detection system. Based upon these criteria, we design a practical low-light detection system that utilizes a realistic low-light synthetic pipeline as well as an auxiliary low-light recovery module. The former can transform any labeled images from existing object detection datasets into their low-light counterparts to facilitate end-to-end training, while the latter can boost the low-light detection performance without adding additional computation cost at inference. Furthermore, we capture a real-world low-light object detection dataset, containing more than two thousand paired low/normal-light images with instance-level annotations to support this line of work. Extensive experiments collectively show the promising results of our designed detection system in very low light, paving the way for real-world object detection in the dark. Our dataset are publicly available at https://github.com/ying-fu/LODDataset.

# Summary. An optional shortened abstract.
summary: "*The 32nd British Machine Vision Conference **(BMVC 2021)**, Virtual, Online*" 

tags:
- Computer Vision
- Computational Photography
featured: false

links:
- name: Talk
  url: https://www.bmvc2021-virtualconference.com/conference/papers/paper_0085.html
url_pdf: "https://www.bmvc2021-virtualconference.com/assets/papers/0085.pdf"
url_code: 'https://github.com/ying-fu/LODDataset'


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

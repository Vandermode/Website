---
title: "Collaborative On-Sensor Array Cameras"
authors:
- "Jipeng Sun"
- "**Kaixuan Wei**†"
- Thomas Eboli
- Congli Wang
- Cheng Zheng
- Zhihao Zhou
- Arka Majumdar
- Wolfgang Heidrich
- Felix Heide
date: "2025-08-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "In *ACM Transactions on Graphics (TOG)*, 2025"

abstract: "Modern nanofabrication techniques have enabled us to manipulate the wavefront of light with sub-wavelength-scale structures, offering the potential to replace bulky refractive surfaces in conventional optics with ultrathin metasurfaces. In theory, arrays of nanoposts provide unprecedented control over manipulating the wavefront in terms of phase, polarization, and amplitude at the nanometer resolution. A line of recent work successfully investigates flat computational cameras that replace compound lenses with a single metalens or an array of metasurfaces a few millimeters from the sensor. However, due to the inherent wavelength dependence of metalenses, in practice, these cameras do not match their refractive counterparts in image quality for broadband imaging, and may even suffer from hallucinations when relying on generative reconstruction methods. In this work, we investigate a collaborative array of metasurface elements that are jointly learned to perform broadband imaging. To this end, we learn a nanophotonics array with 100-million nanoposts that is end-to-end jointly optimized over the full visible spectrum—a design task that existing inverse design methods or learning approaches cannot support due to memory and compute limitations. We introduce a distributed meta-optics learning method to tackle this challenge. This allows us to optimize a large parameter array along with a learned metaatom proxy and a non-generative reconstruction method that is parallax-aware and noise-aware. The proposed camera performs favorably in simulation and in all experimental tests irrespective of the scene illumination spectrum."

# Summary. An optional shortened abstract.
# summary: "*Preprint on arXiv:2002.09611*"
summary:  "*ACM Transactions on Graphics **(SIGGRAPH 2025)**, Vancouver, Canada*"

tags:
- Computational Optics
- Computational Imaging
- Distributed Optimization
featured: false

links:
- name: Project Page
  url: https://light.princeton.edu/publication/collab_array/
url_pdf: https://light.princeton.edu/wp-content/uploads/2025/06/Collab_Array_Cameras.pdf
url_code: 'https://github.com/princeton-computational-imaging/CollaborativeNanoArray'


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

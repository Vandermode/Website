---
title: "Single Image Reflection Removal Exploiting Misaligned Training Data and Network Enhancements"
authors:
- "**Kaixuan Wei**"
- Jiaolong Yang
- Ying Fu
- David Wipf
- Hua Huang
date: "2019-03-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-03-02T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *IEEE Conference on Computer Vision and Pattern Recognition (CVPR)*, 2019

abstract: "Removing undesirable reflections from a single image captured through a glass window is of practical importance to visual computing systems. Although state-of-the-art methods can obtain decent results in certain situations, performance declines significantly when tackling more general real-world cases.  These failures stem from the intrinsic difficulty of single image reflection removal -- the fundamental ill-posedness of the problem, and the insufficiency of densely-labeled training data needed for resolving this ambiguity within learning-based neural network pipelines. In this paper, we address these issues by exploiting targeted network enhancements and the novel use of misaligned data. For the former, we augment a baseline network architecture by embedding context encoding modules that are capable of leveraging high-level contextual clues to reduce indeterminacy within areas containing strong reflections. For the latter, we introduce an alignment-invariant loss function that facilitates exploiting misaligned real-world training data that is much easier to collect.  Experimental results collectively show that our method outperforms the state-of-the-art with aligned data, and that significant improvements are possible when using additional misaligned data. "

# Summary. An optional shortened abstract.
summary: "*The 35th IEEE Conference on Computer Vision and Pattern Recognition **(CVPR 2019)**, Long Beach, USA*"

tags:
- Low-level Vision
- Computational Photography
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: http://openaccess.thecvf.com/content_CVPR_2019/papers/Wei_Single_Image_Reflection_Removal_Exploiting_Misaligned_Training_Data_and_Network_CVPR_2019_paper.pdf
url_code: 'https://github.com/Vandermode/ERRNet'
url_poster: 'files/CVPR19-ERRNet-Poster.pdf'

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
slides: example
---

---
title: "What is Wrong with Continual Learning in Medical Image Segmentation?"
authors:
  - Camila González
  - Nick Lemke
  - Georgios Sakas
  - Anirban Mukhopadhyay

date: "2023-02-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-02-10"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Continual learning protocols are attracting increasing attention from the medical imaging community. In continual environments, datasets acquired under different conditions arrive sequentially; and each is only available for a limited period of time. Given the inherent privacy risks associated with medical data, this setup reflects the reality of deployment for deep learning diagnostic radiology systems. Many techniques exist to learn continuously for image classification, and several have been adapted to semantic segmentation. Yet most struggle to accumulate knowledge in a meaningful manner. Instead, they focus on preventing the problem of catastrophic forgetting, even when this reduces model plasticity and thereon burdens the training process. This puts into question whether the additional overhead of knowledge preservation is worth it - particularly for medical image segmentation, where computation requirements are already high - or if maintaining separate models would be a better solution. We propose UNEG, a simple and widely applicable multi-model benchmark that maintains separate segmentation and autoencoder networks for each training stage. The autoencoder is built from the same architecture as the segmentation network, which in our case is a full-resolution nnU-Net, to bypass any additional design decisions. During inference, the reconstruction error is used to select the most appropriate segmenter for each test image. Open this concept, we develop a fair evaluation scheme for different continual learning settings that moves beyond the prevention of catastrophic forgetting. Our results across three regions of interest (prostate, hippocampus, and right ventricle) show that UNEG outperforms several continual learning methods, reinforcing the need for strong baselines in continual learning research.

# Summary. An optional shortened abstract.
summary: UNEG, a multi-model benchmark for continual learning in medical image segmentation, outperforms existing methods by maintaining separate networks for each training stage and using reconstruction error to select the appropriate model during inference, highlighting the importance of robust baselines over catastrophic forgetting prevention.

tags:
- Continual Learning

featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2010.11008
url_code: 'https://github.com/MECLabTUDA/Lifelong-nnUNet/tree/dev-task_agnostic_cl'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: #'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: #example
---

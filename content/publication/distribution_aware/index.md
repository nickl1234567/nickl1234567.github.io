---
title: 'Distribution-Aware Replay for Continual MRI Segmentation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Nick Lemke
  - Camila González
  - Anirban Mukhopadhyay
  - Martin Mundt


date: '2024-06-30'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-30'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *International Workshop on Personalized Incremental Learning in Medicine*
publication_short: 

abstract: Medical image distributions shift constantly due to changes in patient population and discrepancies in image acquisition. These distribution changes result in performance deterioration; deterioration that continual learning aims to alleviate. However, only adaptation with data rehearsal strategies yields practically desirable performance for medical image segmentation. Such rehearsal violates patient privacy and, as most continual learning approaches, overlooks unexpected changes from out-of-distribution instances. To transcend both of these challenges, we introduce a distribution-aware replay strategy that mitigates forgetting through auto-encoding of features, while simultaneously leveraging the learned distribution of features to detect model failure. We provide empirical corroboration on hippocampus and prostate MRI segmentation.

# Summary. An optional shortened abstract.
summary: A distribution-aware replay strategy for medical image segmentation mitigates forgetting through feature auto-encoding while detecting model failure from out-of-distribution instances, addressing privacy concerns and unexpected distribution shifts.

tags:
  - Continual Learning
  - OOD detection

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2407.21216'
url_code: 'https://github.com/MECLabTUDA/Lifelong-nnUNet/tree/cl_vae'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: #'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  #- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: "Distribution_aware_pdf.pdf"
---

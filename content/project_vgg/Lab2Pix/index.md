---
title: Lab2Pix (TPAMI)
summary: Label-Guided Generative Adversarial Network for Realistic Image Synthesis
tags:
  - Image
date: '2022-06-28T00:00:00Z'
profile: false
share: false


# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: https://github.com/RoseRollZhu/Lab2Pix
url_pdf: https://ieeexplore.ieee.org/document/9810175
url_slides: ''
url_video: ''
url_demo: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

Generating photo-realistic images from labels (e.g., semantic labels or sketch labels) is much more challenging than the general image-to-image translation task, mainly due to the large differences between extremely sparse labels and detail rich images. We propose a general framework Lab2Pix to tackle this issue from two aspects: 1) how to extract useful information from the input; and 2) how to efficiently bridge the gap between the labels and images. Specifically, we propose a Double-Guided Normalization (DG-Norm) to use the input label for semantically guiding activations in normalization layers, and use global features with large receptive fields for differentiating the activations within the same semantic region. To efficiently generate the images, we further propose Label Guided Spatial Co-Attention (LSCA) to encourage the learning of incremental visual information using limited model parameters while storing the well-synthesized part in lower-level features. Accordingly, Hierarchical Perceptual Discriminators with Foreground Enhancement Masks are proposed to toughly work against the generator thus encouraging realistic image generation and a sharp enhancement loss is further introduced for high-quality sharp image generation. We instantiate our Lab2Pix for the task of label-to-image in both unpaired (Lab2Pix-V1) and paired settings (Lab2Pix-V2). Extensive experiments conducted on various datasets demonstrate that our method significantly outperforms state-of-the-art methods quantitatively and qualitatively in both settings.
---
title: Greedy Nature (TMM)
summary: Utilizing Greedy Nature for Multimodal Conditional Image Synthesis in Transformers
tags:
  - VGG
date: '2023-07-17T00:00:00Z'
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
url_code: ''
url_pdf: https://ieeexplore.ieee.org/document/10184483
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

Multimodal Conditional Image Synthesis(MCIS) aims to generate images according to different modalities input and their combination, which allows users to describe their requirements in complementary ways, e.g. segmentation for shapes and text for attributes. Despite satisfying results in MCIS, a non-trivial issue is neglected. Some modalities are fully optimized and dominate the generation, while other modalities are sub-optimized and fail to contribute their complementary information. We coin this phenomenon as Modality Bias. Our analysis reveals that generative models own greedy nature . Specifically, the modality that shares less semantic gap with the synthesized modality will be greedily incorporated and thus takes a larger proportion in synthesis. The main idea of previous works in Modality Bias is to punish the greedy nature, which hurts the performance of dominant modalities and impedes their contribution to multimodal synthesis. Instead, we propose to utilize the greedy nature by setting dominant modalities as guidance for sub-optimized modalities through coordinated feature space, named Coordinated Knowledge Mining. Afterwards, improved uni-modalities are aggregated by fusing coordinated features to further boost the performance of multimodal image synthesis, called Coordinated Knowledge Fusion. Extensive experiments prove that our method not only increases uni-modal performance by a large margin, but also promotes multimodal image synthesis by fully utilizing complementary information from different modalities.
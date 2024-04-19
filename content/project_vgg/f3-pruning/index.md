---
title: F3_Pruning (AAAI)
summary: A Training-Free and Generalized Pruning Strategy towards Faster and Finer Text-to-Video Synthesis
tags:
  - Text-to-Video
date: '2023-12-06T00:00:00Z'
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
url_pdf: https://arxiv.org/abs/2312.03459
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

Recently Text-to-Video (T2V) synthesis has undergone a breakthrough by training transformers or diffusion models on large-scale datasets. Nevertheless, inferring such large models incurs huge costs. Previous inference acceleration works either require costly retraining or are model-specific. To address this issue, instead of retraining we explore the inference process of two mainstream T2V models using transformers and diffusion models. The exploration reveals the redundancy in temporal attention modules of both models,which are commonly utilized to establish temporal relations among frames. Consequently, we propose a training-free and
generalized pruning strategy called F3-Pruning to prune redundant temporal attention weights. Specifically, when aggregate temporal attention values are ranked below a certain ratio, corresponding weights will be pruned. Extensive experiments on three datasets using a classic transformer-based model CogVideo and a typical diffusion-based model Tune A-Video verify the effectiveness of F3-Pruning in inference acceleration, quality assurance and broad applicability.

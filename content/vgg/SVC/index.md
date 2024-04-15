---
title: SVC (ICME)
summary: TRAINING-FREE SEMANTIC VIDEO COMPOSITION VIA PRE-TRAINED DIFFUSION MODEL
tags:
  - Text-to-Video
date: '2024-07-17T00:00:00Z'
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
url_code: https://github.com/ruffiann/Semantic-Video-Composition
url_pdf: https://arxiv.org/html/2401.09195v1
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
The video composition task aims to integrate specified foregrounds and backgrounds from different videos into a harmonious composite. Current approaches, predominantly trained on videos with adjusted foreground color and lighting, struggle to address deep semantic disparities beyond superficial adjustments, such as domain gaps. Therefore, we propose a training-free pipeline employing a pre-trained diffusion model imbued with semantic prior knowledge, which can process composite videos with broader semantic disparities. Specifically, we process the video frames in a cascading manner and handle each frame in two processes with the diffusion model. In the inversion process, we propose Balanced Partial Inversion to obtain generation initial points that balance reversibility and modifiability. Then, in the generation process, we further propose Inter-Frame Augmented attention to augment foreground continuity across frames. Experimental results reveal that our pipeline successfully ensures the visual harmony and inter-frame coherence of the outputs, demonstrating efficacy in managing broader semantic disparities.
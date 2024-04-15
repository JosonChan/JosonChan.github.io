---
title: EchoReel (arXiv)
summary: Enhancing Action Generation of Existing Video Diffusion Models
tags:
  - Text-to-Video
date: '2024-03-18T00:00:00Z'
profile: false
share: false

# Optional external URL for project (replaces project detail page).
external_link: ''


image:
  focal_point: Right

links:
  - icon:
    icon_pack: fab
    name: demo
    url: https://liujianzhi.github.io/EchoReel-demo/
url_code: https://github.com/liujianzhi/EchoReel
url_pdf: https://arxiv.org/abs/2403.11535
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ''
---

Recent large-scale video datasets have facilitated the generation of diverse open-domain videos of Video Diffusion Models (VDMs). Nonetheless, the efficacy of VDMs in assimilating complex knowledge from these datasets remains constrained by their inherent scale, leading to suboptimal comprehension and synthesis of numerous actions. In this paper, we introduce EchoReel, a novel approach to augment the capability of VDMs in generating intricate actions by emulating motions
from pre-existing videos, which are readily accessible from databases or online repositories. EchoReel seamlessly integrates with existing VDMs, enhancing their ability to produce realistic motions without compromising their fundamental capabilities. Specifically, the Action Prism (AP), is introduced to distill motion information from reference videos, which requires training on only a small dataset. Leveraging the knowledge from pre-trained VDMs, EchoReel incorporates new action features into VDMs through the additional layers, eliminating the need for any further fine-tuning of untrained actions. Extensive experiments demonstrate that EchoReel is not merely replicating the whole content from references, and it significantly improves the generation of realistic actions, even in situations where existing VDMs might directly fail.
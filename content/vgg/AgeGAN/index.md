---
title: AgeGAN++
summary: Face Aging and Rejuvenation With Dual Conditional GANs
tags:
  - VGG
date: '2024-04-12T00:00:00Z'
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
url_code: https://github.com/Sherry-JQ/AgeGAN
url_pdf: https://ieeexplore.ieee.org/document/9354597/
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

Face aging and rejuvenation is applied to predict what a person looks like at different ages. While prior work brought about a significant progress in this topic, there are two central problems remaining to be solved : 1) most prior works require sequential data during training, while it is very rare in
existing datasets; and 2) how to render an aging face and preserve personality at the same time. To deal with these problems, we develop a novel dual conditional GANs mechanism, thus aging faces can be trained with multiple sets of unlabeled facial images of different ages. Our basic architecture is AgeGAN, in which the primal conditional GAN converts input faces to other ages based on relevant age conditions, and the dual conditional GAN learns to invert the task. We further improve our networks, termed AgeGAN++, in which we share the weights between the primal part and the dual part to to streamline the model. Moreover, in order to get more sensible results, a representation disentanglement component is integrated with the latent facial representation, and an enhanced discriminator is applied on the generated process. In addition, we firstly perform an interpolation experiment to demonstrate that our generators are powerful and effective for face aging and rejuvenation. Experimental results on four public datasets demonstrate the appealing performance of the proposed methods by comparing with the state-of-the-art methods.

---
title: EvoGAN (ACM MM)
summary: An Evolutionary GAN for Face Aging and Rejuvenation
tags:
  - VGG
date: '2021-05-03T00:00:00Z'
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
url_pdf: https://dl.acm.org/doi/10.1145/3444685.3446323
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

In biology, evolution is the gradual change in the characteristics of a species over several generations. It has two properties: 1) The change is gradual, and 2) long-term changes are relied on shortterm changes. Face aging/rejuvenation, which renders younger or elder facial images, follows the principles of evolution. Inspired by this, we propose an Evolutionary GANs (EvoGAN) for face aging/rejuvenation by making each age transformation smooth and decomposing a long-term transformation into several short-terms. Specifically, since short-term facial changes are gradual and relatively easy to render, we first divide the ages into several groups (i.e., chronologically from child, adult to elder). Then, for each pair of adjacent groups, we design two age transforms for face aging and rejuvenation, which are supposed to preserve personal identify information and predict age-specific characteristics. Compared with the mainstream for face aging/rejuvenation, i.e., conditional GANs based methods utilizing one-hot age vector as an age transformation condition, our smooth EvoGAN abandons this condition
and can better predict age-specific factors (e.g., the drastic shape and appearance change from an adult to a child). To evaluate our EvoGAN, we construct a challenging dataset FFHQ_Age. Extensive experiments conducted on the dataset demonstrate that our model is able to generate significantly better results than the state-of-the art methods qualitatively and quantitatively.

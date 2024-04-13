---
title: SIMGAN (TMM)
summary: Structuring Image for Text-to-Image Attributes Manipulation
tags:
  - VGG
date: '2022-11-04T00:00:00Z'
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
url_code: https://github.com/qikizh/SIMGAN
url_pdf: https://ieeexplore.ieee.org/document/9939081
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
Manipulating visual attributes of an image through a natural language description, known as text-to-image attributes manipulation (T2AM), is a challenging task. However, existing approaches tend to search the whole image to manipulate the target instance indicated by a description, thus they often fail to locate and manipulate the accurate text-relevant regions, and even disturb the text-irrelevant contents, e.g. texture and background. Meanwhile, the model efficiency needs to be improved. To tackle the above issues, we introduce a novel yet simple GAN-based approach, namely Structuring Image for Manipulating (SIMGAN), to narrow down the optimization areas from external to internal. It consists of two major components: 1) External Structuring (ExST), a pretrained segmentation network, for recognizing and separating the target instances and background from an image; and 2) Internal Structuring (InST) for seeking out and editing the text-relevant attributes of the target instances based on the given description and masked hierarchical image representations from ExST. Specifically, the InST structures target instances from outline to detail by firstly drawing the sketch and colors underpainting of instances with an Outline-Oriented Structuring (OuST), and then enhancing the text-relevant attributes and elaborating on details with a Detail-Oriented Structuring (DeST). Extensive experiments on benchmark datasets demonstrate that our framework significantly outperforms state-of-the-art both quantitatively and qualitatively. Compared with the state-of-the art method ManiGAN, our approach reduces the training time by 88%, while the inferring time is three times faster. In addition, our approach is easily extended to solve the instance-level image-to-image translation problem, and the results exhibit the versatility and effectiveness of our approach
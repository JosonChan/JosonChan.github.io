---
title: MGD-GAN (IJCAI)
summary: Towards Unspervised Deformable-Instances Image-to-Image Translation
tags:
  - Image
date: '2021-12-06T00:00:00Z'
profile: false
share: false


# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  focal_point: Right

# links:
#   - icon:
#     icon_pack: fab
#     name: Demo
#     url: https://litaoguo.github.io/Make-A-Storyboard.github.io/
url_code: https://github.com/sitongsu/MGD_GAN
url_pdf: https://www.ijcai.org/proceedings/2021/0139.pdf
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

Replacing objects in images is a practical functionality of Photoshop, e.g., clothes changing. This task is defined as Unsupervised Deformable-Instances Image-to-Image Translation (UDIT), which maps multiple foreground instances of a source domain to a target domain, involving significant changes in shape. In this paper, we propose an effective pipeline named Mask-Guided Deformableinstances GAN (MGD-GAN) which first generates target masks in batch and then utilizes them to synthesize corresponding instances on the background image, with all instances efficiently translated and background well preserved. To promote the quality of synthesized images and stabilize the training, we design an elegant training procedure which transforms the unsupervised mask-to-instance process into a supervised way by creating paired examples. To objectively evaluate the performance of UDIT task, we design new evaluation metrics which are based on the object detection. Extensive experiments on four datasets demonstrate the significant advantages of our MGD-GAN over existing methods both quantitatively and qualitatively. Furthermore, our training time consumption is hugely reduced compared to the state-of-the-art.
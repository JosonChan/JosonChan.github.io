---
title: Fully Functional (ACM MM)
summary: Fully Functional Image Manipulation Using Scene Graphs in A Bounding-Box Free Way
tags:
  - Image
date: '2021-10-17T00:00:00Z'
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
url_pdf: https://dl.acm.org/doi/abs/10.1145/3474085.3475326
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

Recently, performing semantic editing of an image by modifying a scene graph has been proposed to support high-level image manipulation, and plays an important role for image generation. However, existing methods are all based on bounding boxes, and they suffer from the bounding box constraint. First, a bounding box often
involves other instances (e.g, objects or environments) which do not need to be modified, but existing methods manipulate all the contents included in the bounding box. Secondly, prior methods fail to support adding instances when the bounding box of the target instance cannot be provided. To address the two issues above,
we propose a novel bounding box free approach, which consists of two parts: a Local Bounding Box Free (Local-BBox-Free) Mask Generation and a Global Bounding Box Free (Global-BBox-Free) Instance Generation. The first part relieves the model of reliance on bounding boxes by generating the mask of the target instance
to be manipulated without using the target instance bounding box. This enables our method to be the first to support fully functional image manipulation using scene graphs, including adding, removing, replacing and repositing instances. The second part is designed to synthesize the target instance directly from the generated mask and then paste it back to the inpainted original image using the generated mask, which preserves the unchanged part to the largest extent and precisely controls the target instance generation. Extensive experiments on Visual Genome and COCO-Stuff demonstrate that our model significantly surpasses the state-of-the-art both quantitatively and qualitatively.

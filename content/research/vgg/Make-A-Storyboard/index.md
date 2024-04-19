---
title: Make-A-Storyboard (arXiv)
summary: A General Framework for Storyboard with Disentangled and Merged Control 
tags:
  - Text-to-Image
date: '2023-12-06T00:00:00Z'
profile: false
share: false


# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  focal_point: Right

links:
  - icon:
    icon_pack: fab
    name: Demo
    url: https://litaoguo.github.io/Make-A-Storyboard.github.io/
url_code: ''
url_pdf: https://arxiv.org/abs/2312.07549
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

Story Visualization aims to generate images aligned with story prompts, reflecting the coherence of storybooks through visual consistency among characters and scenes.Whereas current approaches exclusively concentrate on characters and neglect the visual consistency among contextually correlated scenes, resulting in independent character images without inter-image this http URL tackle this issue, we propose a new presentation form for Story Visualization called Storyboard, inspired by film-making, as illustrated in Fig.1.Specifically, a Storyboard unfolds a story into visual representations scene by scene. Within each scene in Storyboard, characters engage in activities at the same location, necessitating both visually consistent scenes and characters.For Storyboard, we design a general framework coined as Make-A-Storyboard that applies disentangled control over the consistency of contextual correlated characters and scenes and then merge them to form harmonized images.Extensive experiments demonstrate 1) Effectiveness.the effectiveness of the method in story alignment, character consistency, and scene correlation; 2) Generalization. Our method could be seamlessly integrated into mainstream Image Customization methods, empowering them with the capability of story visualization.
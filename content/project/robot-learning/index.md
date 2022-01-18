---
title: Multimodal End to End Autonomous Driving via Conditional Imitation Learning
summary: Robot Learning Final Project - Charles Nimo & Alex Zuzow.
tags:
- Robot Learning
- Deep Learning
- Reinforcement Learning
- Robotics
date: "2021-12-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:

url_code: ""
url_pdf: "files/autonomous_driving.pdf"
url_slides: ""
url_video: "https://youtu.be/Z0tCkyDkwwQ"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

One of the key problems of autonomous vehicles is how to represent the world around us in a digestible way. There are many modalities to choose from, each of which gives a different context for a situation. Therefore it is important to choose the modalities which give the most important information gain. We explore the impact of adding and removing modalities with respect to early multimodal fusion paradigms in the context of conditional imitation learning. We test the impact of four modalities, RGB, LiDAR, optical flow, and velocity. Our model consists of two parts, a feature encoder, and a autoregressive waypoint predictor. There are two encoder architectures used in our experiments, the first is simply a pre-trained EfficientNet while the second is an EfficientNet that feeds into a transformer at the last block. We find that optical flow improves the model's performance although it becomes very unstable while training due to harsh augmentations of RGB images. Our conclusion is that optical flow provides key representation for end-to-end multimodal conditional imitation learning models; however, perturbations of RGB images drastically decrease model performance, effectively only adding noise to the model.

You can find our {{< staticref "files/autonomous_driving.pdf" "newtab" >}}paper here{{< /staticref >}},  and our video {{< staticref "https://youtu.be/Z0tCkyDkwwQ" "newtab" >}}presentation here{{< /staticref >}}.

---
title: Real-Time Optical Flow Estimation
summary: Advanced Computer Vision Final Project - Charles Nimo & Alex Zuzow
tags:
- Computer Vision
- Deep Learning
date: "2021-12-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/princenimo/Real-Time-Optical-Flow-Estimation
url_code: ""
url_pdf: "files/comp_vision.pdf"
url_slides: ""
url_video: "https://youtu.be/YT_fP2no8LM"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:
---

  Major progress has been made for estimating optical flow using deep neural networks in recent years. However, optical flow estimation is an extremely computationally expensive task as it requires computing estimates of the motion between two time steps of a video or a sequence of images. We build upon the previous work RAFT which is the current state-of-the-art approach for optical flow estimation. In this work, by  applying techniques such as pruning, quantization, and distillation we aim to improve the inference time of RAFT. Our experiments show that our model achieves similar performance while also being faster and light weight in comparison to original RAFT architecture.

   You can find our code in this {{< staticref "https://github.com/princenimo/Real-Time-Optical-Flow-Estimation" "newtab" >}}github repo{{< /staticref >}}, {{< staticref "files/comp_vision.pdf" "newtab" >}}paper here{{< /staticref >}},  and our video {{< staticref "https://youtu.be/YT_fP2no8LM" "newtab" >}}presentation here{{< /staticref >}}.

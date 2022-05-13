---
abstract: |-
  In this work, we propose a long-term UAV de-
  tection and tracking system from RGB-Thermal (RGB-T)
  sequences. The system consists of a high resolution daylight
  visible camera and a thermal camera mounted on a UAV
  (airborne), for the detection of flying intruders. The framework
  is composed of the detection and tracking modules. The primary
  detection module based on the YOLOv4 method is optimized
  for small UAV detection and works both on the RGB and
  Thermal domains. To alleviate the issue of temporarily losing
  the intruder, we employ a discriminative correlation filter based
  object tracker, which is initialized with the output of the
  detection module and tracks the target at a higher speed.
  The dimensionality reduction is applied to the features for
  tracking to improve the performance. Meanwhile, we utilize
  the infrared signal as a spatial regularization term of the
  tracker to suppress the boundary effects that stem from circular
  convolution, leading to a more robust appearance model and
  tracking performance. The tracker is efficiently optimized via
  the Alternating Direction Method of Multiplier (ADMM). We
  evaluate our method on multiple visual and thermal tracking
  benchmarks, as well as field tests with a prototype platform. The
  experimental results demonstrate that our system can achieve
  accurate, robust and continuous detection and tracking of UAVs
  under complex circumstances.
slides: ""
url_pdf: "https://ieeexplore.ieee.org/document/9476750"
publication_types:
  - "1"
authors:
  - Daitao Xing
  - Athanasios Tsoukalas
  - Nikolaos Giakoumidis
  - Anthony Tzes.
author_notes: []
publication: in *THE 2021 INTERNATIONAL CONFERENCE ON UNMANNED AIRCRAFT SYSTEMS*
summary:     In this work, we propose a long-term UAV de-
  tection and tracking system from RGB-Thermal (RGB-T)
  sequences. The system consists of a high resolution daylight...
url_dataset: ""
url_project: ""
publication_short: In *ICUAS2021*
url_source: ""
url_video: ""
title: Computationally Efficient RGB-T UAV Detection and Tracking System
doi: ""
featured: false
tags: []
projects: []
image:
  caption: "ICUAS2021"
  focal_point: ""
  preview_only: false
date: 2021-04-16T00:00:00.000Z
url_slides: ""
publishDate: 2021-04-16T00:00:00Z
url_poster: ""
url_code: ""
---

---
abstract: |-
  Recent visual object trackers provide strong dis-
  criminability towards accurate tracking under challenging sce-
  narios while neglecting the inference efficiency. Those methods
  handle all inputs with identical computation and fail to reduce
  intrinsic computational redundancy, which constrains their
  deployment on Unmanned Aerial Vehicles (UAVs). In this
  work, we propose a dynamic tracker which selectively activates
  the individual model components and allocates computation
  resources on demand during the inference, which allows deep
  network inference on onboard-CPU at real-time speed. The
  tracking pipeline is divided into several stages, where each stage
  consists of a transformer-based encoder that generates a robust
  target representation by learning pixels interdependence. An
  adaptive network selection module controls the propagation
  routing path determining the optimal computational graph
  according to confidence-based criteria. We further propose
  a spatial adaptive attention network to avoid computational
  overhead in the transformer encoder, where the self-attention
  only aggregates the dependencies information among selected
  points. Our model achieves a harmonious proportion between
  accuracy and efficiency for dealing with varying scenarios,
  leading to notable advantages over static models with a fixed
  computational cost. Comprehensive experiments on aerial and
  prevalent tracking benchmarks achieve competitive results
  while operating at high speed, demonstrating its suitability on
  UAV-platforms which do not carry a dedicated GPU.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Daitao Xing
  - Athanasios Tsoukalas
  - Nikolaos Evangeliou
  - Nikolaos Giakoumidis
  - Anthony Tzes
author_notes: []
publication: in *THE 2022 INTERNATIONAL CONFERENCE ON UNMANNED AIRCRAFT SYSTEMS*
summary:   Recent visual object trackers provide strong dis-
  criminability towards accurate tracking under challenging sce-
  narios while neglecting the inference efficiency. Those methods
  handle all inputs with identical computation and fail to reduce
  intrinsic computational redundancy, which constrains their
  deployment on Unmanned Aerial Vehicles (UAVs). In this
  work, we propose a dynamic tracker which selectively activates
  the individual model components and allocates computation
  resources on demand during the inference, which allows deep
  network inference on onboard-CPU at real-time speed. The
  tracking pipeline is divided into several stages, where each stage
  consists of a transformer-based encoder that generates a robust
  target representation by learning pixels interdependence. An
  adaptive network selection module controls the propagation
  routing path determining the optimal computational graph
  according to confidence-based criteria. We further propose
  a spatial adaptive attention network to avoid computational
  overhead in the transformer encoder, where the self-attention
  only aggregates the dependencies information among selected
  points. Our model achieves a harmonious proportion between
  accuracy and efficiency for dealing with varying scenarios,
  leading to notable advantages over static models with a fixed
  computational cost. Comprehensive experiments on aerial and
  prevalent tracking benchmarks achieve competitive results
  while operating at high speed, demonstrating its suitability on
  UAV-platforms which do not carry a dedicated GPU.
url_dataset: ""
url_project: ""
publication_short: In *ICUAS2022*
url_source: ""
url_video: ""
title: Siamese Adaptive Transformer Network for Real-Time Aerial Tracking
doi: ""
featured: false
tags: []
projects: []
image:
  caption: "SiamATN"
  focal_point: ""
  preview_only: false
date: 2022-04-16T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00Z
url_poster: ""
url_code: ""
---
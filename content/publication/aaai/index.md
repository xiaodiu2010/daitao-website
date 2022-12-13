---
abstract: |-
  In this work, we explore the process of designing a long-term drone surveillance system by fusing object detection, tracking and classification methods. Given a video stream from an RGB-camera, a detection module based on YOLOV5 is trained for finding drones within its field of view. Although in drone detection, high accuracy and robustness is achieved with the underlying complex architecture, the detection speed is hindered on ultra HD-streams. To solve this problem, we integrate a high efficient object tracker to update target status while avoiding running the detection at each frame. Benefited from lightweight backbone networks with powerful Transformer design, the object tracker achieves real-time speed on standalone CPU devices. Moreover, a drone classification model is applied on the output of the detection and tracking mechanisms to further distinguish drones from other background distractors (birds, balloons). By leveraging inference optimization with TensorRT and ONNX, our system achieves extremely high inference speed on NVIDIA GPUs. A ROS package is designed to integrate the aforementioned components together and provide a flexible, end-to-end drone surveillance tool for real-time applications. Comprehensive experiments on both standard benchmarks and field tests demonstrate the effectiveness and stability of proposed system.
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Daitao Xing
  - Jingling Shen
  - Chiuman Ho
  - Anthony Tzes
author_notes: []
publication: in *The Thirty-Seventh AAAI Conference on Artificial Intelligence*
summary:     The exploration of mutual-benefit cross-domains has shown great potential toward accurate self-supervised depth estimation. In this work, we revisit feature fusion ....
url_dataset: ""
url_project: ""
publication_short: In *AAAI2023*
url_source: ""
url_video: ""
title: Semantic-Aware Region of Interest Transformer for Efficient
Self-Supervised Monocular Depth Estimation
doi: ""
featured: false
tags: []
projects: []
image:
  caption: "AAAI"
  focal_point: ""
  preview_only: false
date: 2022-11-18T00:00:00.000Z
url_slides: ""
publishDate: 2022-11-18T00:00:00.000Z
url_poster: ""
url_code: ""
---

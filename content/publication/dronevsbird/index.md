---
abstract: |-
In this work, we explore the process of designing a long-term
drone surveillance system by fusing object detection, tracking and classi-
fication methods. Given a video stream from an RGB-camera, a detection
module based on YOLOV5 is trained for finding drones within its field
of view. Although in drone detection, high accuracy and robustness is
achieved with the underlying complex architecture, the detection speed
is hindered on ultra HD-streams. To solve this problem, we integrate a
high efficient object tracker to update target status while avoiding run-
ning the detection at each frame. Benefited from lightweight backbone
networks with powerful Transformer design, the object tracker achieves
real-time speed on standalone CPU devices. Moreover, a drone classi-
fication model is applied on the output of the detection and tracking
mechanisms to further distinguish drones from other background dis-
tractors (birds, balloons). By leveraging inference optimization with Ten-
sorRT and ONNX, our system achieves extremely high inference speed
on NVIDIA GPUs. A ROS package is designed to integrate the afore-
mentioned components together and provide a flexible, end-to-end drone
surveillance tool for real-time applications. Comprehensive experiments
on both standard benchmarks and field tests demonstrate the effective-
ness and stability of proposed system
slides: ""
url_pdf: ""
publication_types:
  - "1"
authors:
  - Daitao Xing
  - Halil Utku Unlu
  - Nikolaos Evangeliou
  - Anthony Tzes.
author_notes: []
publication: in *THE 2022 INTERNATIONAL CONFERENCE ON IMAGING ANALYSIS AND PROCESSING*
summary:   In this work, we explore the process of designing a long-term
drone surveillance system by fusing object detection, tracking and classi-
fication methods. Given a video stream from an RGB-camera, a detection
module based on YOLOV5 is trained for finding drones within its field
of view. Although in drone detection, high accuracy and robustness is
achieved with the underlying complex architecture, the detection speed
is hindered on ultra HD-streams. To solve this problem, we integrate a
high efficient object tracker to update target status while avoiding run-
ning the detection at each frame. Benefited from lightweight backbone
networks with powerful Transformer design, the object tracker achieves
real-time speed on standalone CPU devices. Moreover, a drone classi-
fication model is applied on the output of the detection and tracking
mechanisms to further distinguish drones from other background dis-
tractors (birds, balloons). By leveraging inference optimization with Ten-
sorRT and ONNX, our system achieves extremely high inference speed
on NVIDIA GPUs. A ROS package is designed to integrate the afore-
mentioned components together and provide a flexible, end-to-end drone
surveillance tool for real-time applications. Comprehensive experiments
on both standard benchmarks and field tests demonstrate the effective-
ness and stability of proposed system
url_dataset: ""
url_project: ""
publication_short: In *ICIAP2022*
url_source: ""
url_video: ""
title: Drone Surveillance using Detection, Tracking and Classification Techniques
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
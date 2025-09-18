---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'SeDA: Secure and Efficient DNN Accelerators with Hardware/Software Synergy'
subtitle: ''
summary: ''
authors:
- Wei Xuan
- Zhongrui Wang
- Lang Feng
- Ning Lin
- Zihao Xuan
- admin
- Tsung-Yi Ho
- Yuzhong Jiao
- Luhong Liang
tags:
- memory protection
- secure DNN accelerators
- confidentiality and integrity
- deep neural networks
categories: []
date: 2025-02-25T14:04:38+08:00
lastmod: 2025-02-25T14:04:38+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: 2025-02-25T14:04:38+08:00
publication_types:
- '1'
abstract: 'Ensuring the confidentiality and integrity of DNN accelerators is paramount across various scenarios spanning autonomous driving, healthcare, and finance. However, current security approaches typically require extensive hardware resources, and incur significant off-chip memory access overheads. This paper introduces SeDA, which utilizes 1) a bandwidth-aware encryption mechanism to improve hardware resource efficiency, 2) optimal block granularity through intra-layer and inter-layer tiling patterns, and 3) a multi-level integrity verification mechanism that minimizes, or even eliminates, memory access overheads. Experimental results show that SeDA decreases performance overhead by over 12% for both server and edge neural processing units (NPUs), while ensuring robust scalability.11SeDA source code:https://github.com/wayne4s/seda.git'
publication: '*Proceedings of the 62nd Design Automation Conference*'
publication_short: '*DAC*'
doi: '10.1109/DAC63849.2025.11133180'

url_pdf: https://flians.github.io/pdf/seda.pdf
url_code: https://github.com/Anonymousview/seda
---

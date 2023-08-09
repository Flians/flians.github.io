---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'JRouter: A Multi-Terminal Hierarchical Length-Matching Router under Planar
  Manhattan Routing Model for RSFQ Circuits'
subtitle: ''
summary: ''
authors:
- Xinda Chen
- admin
- Junying Huang
- Huawei Cao
- Zhimin Zhang
- Xiaochun Ye
- Tsung-Yi Ho
- Dongrui Fan
tags:
- rsfq
- length-matching
- routing
- superconducting logic
categories: []
date: '2023-06-05'
lastmod: 2023-06-15T23:54:56+08:00
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
publishDate: '2023-06-15T15:54:56.390380Z'
publication_types:
- '1'
abstract: Superconducting rapid single-flux-quantum (RSFQ) logic has shown great potential
  for high-energy-efficient computing systems. To ensure correct operations at ultra-high
  frequencies, it is necessary to incorporate length-matching constraints into the
  routing problem. Existing routing algorithms, however, can only address 2-pin connections
  or support the conventional horizontal/vertical routing model, which substantially
  limits the optimization space for routing solutions. This paper presents JRouter,
  an RSFQ router that considers the two-layer planar Manhattan routing model while
  simultaneously coping with splitter (SPL) placement and length-matching multi-terminal
  routing. JRouter contains a track-assignment-based initial routing that minimizes
  the initial routing width while avoiding conflicts in the horizontal constraint
  graph. Moreover, JRouter implements an SPL-tree-based hierarchical routing with
  an iterative maximum-flow-based formulation to insert the detours for multi-terminal
  routing. A routing region extension algorithm is also developed to insert the detours
  for unsatisfied connections. According to the experimental results, JRouter achieves
  an average routing width reduction of 35.71% and 22.46% on a 16-bit RSFQ Sklansky
  adder compared to Kito's and Kou's routing algorithms. For randomly generated benchmarks,
  JRouter reduces the routing width by an average of 38.77%, 38.20%, 21.65%, and 7.01%
  compared to Kito's, Kou's, and two of Yan's routing algorithms, respectively, while
  maintaining reasonable runtime.
publication: '*Proceedings of the 2023 on Great Lakes Symposium on VLSI*'
publication_short: '*GLSVLSI*'
doi: 10.1145/3583781.3590267
links:
- name: URL
  url: https://doi.org/10.1145/3583781.3590267
---

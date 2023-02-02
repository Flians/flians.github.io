---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Global Optimization Algorithm for Buffer and Splitter Insertion in Adiabatic
  Quantum-Flux-Parametron Circuits
subtitle: ''
summary: ''
authors:
- admin
- Mengmeng Wang
- Yirong Kan
- Nobuyuki Yoshikawa
- Tsung-Yi Ho
- Olivia Chen
tags:
- buffer and splitter insertion
- superconducting electronics
- AQFP
categories: []
date: '2023-01-01'
lastmod: 2023-02-02T01:09:30+08:00
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
publishDate: '2023-01-31T17:09:30.737080Z'
publication_types:
- '1'
abstract: As a highly energy-efficient application of low-temperature superconductivity,
  the adiabatic quantum-flux-parametron (AQFP) logic circuit has characteristics of
  extremely low-power consumption, making it an attractive candidate for extremely
  energy-efficient computing systems. Since logic gates are driven by the alternating
  current (AC) serving as the clock signal in AQFP circuits, plenty of AQFP buffers
  are required to ensure that the dataflow is synchronized at all logic levels of
  the circuit. Meanwhile, since the currently developed AQFP logic gates can only
  drive a single output, splitters are required by logic gates to drive multiple fan-outs.
  These gates take up a significant amount of the circuit's area and delay. This paper
  proposes a global optimization algorithm for buffer and splitter (B/S) insertion
  to address the issues above. The B/S insertion is first identified as a combinational
  optimization problem, and a dynamic programming formulation is presented to find
  the global optimal solution. Due to the limitation of its impractical search space,
  an integer linear programming formulation is proposed to explore the global optimization
  of B/S insertion approximately. Experimental results on the ISCAS'85 and simple
  arithmetic benchmark circuits show the effectiveness of the proposed method, with
  an average reduction of 8.22% and 7.37% in the number of buffers and splitters inserted
  compared to the state-of-the-art methods from ICCAD'21 and DAC'22, respectively.
publication: '*Proceedings of the 28th Asia and South Pacific Design Automation Conference*'
doi: 10.1145/3566097.3567936
links:
- name: URL
  url: https://doi.org/10.1145/3566097.3567936
---

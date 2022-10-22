---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Equivalence Checking for Superconducting RSFQ Logic Circuits
subtitle: ''
summary: ''
authors:
- admin
- Junying Huang
- Zhi-Min Zhang
tags:
- logic cone
- smt
- rapid single-flux-quantum (RSFQ)
- superconducting circuits
- equivalence checking
categories: []
date: '2021-06-22'
lastmod: 2022-10-22T18:01:51+08:00
featured: false
draft: false
note: Best Paper Nomination
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
publishDate: '2022-10-22T10:01:51.330571Z'
publication_types:
- '1'
abstract: Equivalence checking is a key component of the verification methodology
  for digital circuit designs. In this paper, we propose an equivalence checking framework
  for superconducting rapid single-flux-quantum (RSFQ) logic circuits which include
  acyclic circuits and bit-slice-based cyclic circuits. It consists of a structure
  checker and a logic checker. The structure checker is used to check whether the
  circuit meets the design rules of superconducting RSFQ logic circuits. The logic
  checker can be used to check whether two RSFQ gate-level circuits have the same
  logic function. For the logic checker, we propose a logic equivalence checking method
  based on logic cone partition. The circuit network is simplified layer by layer
  and iteratively partitioned into logic cones, each of which is verified by the SMT
  solver. The experimental results show the feasibility of our approach on superconducting
  RSFQ logic circuits.
publication: '*Proceedings of the 2021 on Great Lakes Symposium on VLSI*'
doi: 10.1145/3453688.3461486
links:
- name: URL
  url: https://doi.org/10.1145/3453688.3461486
---

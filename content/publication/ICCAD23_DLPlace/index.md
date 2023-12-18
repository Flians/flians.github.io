---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DLPlace: A Delay-Line Clocking-Based Placement Framework for AQFP Circuits'
subtitle: ''
summary: ''
authors:
- admin
- Olivia Chen
- Bei Yu
- Nobuyuki Yoshikawa
- Tsung-Yi Ho
tags: []
categories: []
date: '2023-08-14'
lastmod: 2023-12-18T14:04:38+08:00
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
publishDate: '2023-12-18T06:04:38.252710Z'
publication_types:
- '1'
abstract: Addressing the pressing need for energy-efficient computing technologies, innovations such as Josephson junctions-based superconducting logic circuits, particularly the Adiabatic Quantum-Flux-Parametron (AQFP) logic, have sparked increased research interest. AQFP logic, boasting superior energy efficiency, faces unique design challenges. The current 4-phase clocking scheme results in considerable circuit latency, a problem further amplified with larger logic depth in the circuit. A novel delay-line clocking scheme proposes increasing the number of clock phases, which could significantly improve circuit latency but also risks more severe timing violations. To address this issue, this paper proposes DLPlace, the first placement framework tailored for the delay-line clocking scheme, aiming to boost the performance of AQFP circuits. DLPlace formulates timing-aware global placement as a Lagrangian problem, targeting minimizing the circuit latency, to determine the positions of all gates and the delays of delay lines by the subgradient method. A timing-aware detailed placement approach is then proposed, where DLPlace introduces a row-wise gate order rearrangement method to reduce wirelength and timing violations in AQFP circuits. Furthermore, a dynamic programming approach is employed to achieve wirelength and timing legalization, thereby addressing the unique requirements of AQFP logic. The effectiveness of DLPlace is validated through AQFP benchmark experiments, demonstrating a significant reduction in both hardware footprint and circuit latency compared to the baselines. This new framework paves the way for the further optimization of AQFP circuit performance, offering a promising solution to the physical design challenges in superconductive electronics-based computing.
publication: '*Proceedings of the 42th IEEE/ACM International Conference on Computer-Aided Design*'
publication_short: '*ICCAD*'
doi: 10.1109/ICCAD57390.2023.10323698
url_pdf: https://flians.github.io/pdf/DLPlace.pdf
---

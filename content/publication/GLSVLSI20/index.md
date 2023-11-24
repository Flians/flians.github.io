---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Design Automation Methodology from RTL to Gate-Level Netlist and Schematic
  for RSFQ Logic Circuits
subtitle: ''
summary: ''
authors:
- admin
tags:
- layer assignment
- logic synthesis
- schematic generation
- RSFQ
- superconducting logic circuits
- design automation
categories: []
date: '2020-09-07'
lastmod: 2022-10-22T18:02:12+08:00
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
publishDate: '2022-10-22T10:02:11.977411Z'
publication_types:
- '1'
abstract: The superconducting rapid single flux quantum (RSFQ) logic circuit has the
  characteristics of high speed and low power consumption, making it an attractive
  candidate for future supercomputers. However, computer-aided design (CAD) tools
  for CMOS cannot be directly applied to RSFQ logic due to their distinct properties.
  For instance, the RSFQ logic gate can work properly when all its fan-ins have the
  same logic level. This paper presents the design flow from RTL to RSFQ logic netlist
  and schematic. First, we implement logic synthesis for RSFQ logic circuits. It achieves
  path balancing while minimizing the number of DFFs. In addition, we propose an automatic
  schematic generator for the RSFQ logic circuits. It converts the synthesized netlist
  into its equivalent schematic. A layer assignment algorithm is proposed, which makes
  all gates layered in the order of the clock arrival time. Experimental results with
  ISCAS85 and EPFL benchmarks along with some Kogge-Stone adders have shown a 29.2%
  reduction in the number of DFFs over the breadth-first first search; moreover, 59.57%
  and 5.3% decrease in the number of layers of the schematic and number of edge crossings
  over the ELK tool.
publication: '*Proceedings of the 2020 on Great Lakes Symposium on VLSI*'
publication_short: '*GLSVLSI*'
doi: 10.1145/3386263.3406898
links:
- name: URL
  url: https://doi.org/10.1145/3386263.3406898
---

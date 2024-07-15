---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'RABER: Reliability-Aware Bayesian-Optimization-based Control Layer Escape Routing for Flow-based Microfluidics'
subtitle: ''
summary: ''
authors:
- Siyuan Liang
- admin
- Mengchu Li
- Sun-Ming Tseng
- - Ulf Schlichtmann
- Tsung-Yi Ho
tags:
- microfluidics
- escape routing
- bayesian optimization
categories: []
date: '2024-06-28'
lastmod: 2024-7-15T14:02:19+08:00
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
publishDate: '2024-12-18T06:02:19.292060Z'
publication_types:
- '1'
abstract: After decades of development, flow-based microfluidic biochips have become one of the most promising platforms for biochemical experiments. Control ports, which are remarkably area-consuming punch holes, are interfaces to external pneumatic controllers. To prevent the inserted outer catheters from hindering microscopic observation during experiments, control ports are placed on chip boundaries in practice. In this paper, we propose a practical and novel control layer escape routing methodology, which efficiently connects microvalves to user-specified boundaries. Particularly, the proposed methodology groups certain microvalves, and constructs a tree to connect them with the same control port, which is regarded as the root of the tree. Clustering more microvalves into the same group can reduce the usage of control ports, but will lead to more intensive connections among microvalves, which becomes larger obstacles for the routing of other microvalves outside the group, thereby reducing the routability. To derive an optimized tradeoff between the control port usage and the routability, we adapt a hierarchical clustering algorithm with a dynamically changing threshold that ascertains the closeness of the microvalves. We also adopt the Bayesian optimization (BO) to determine the optimized routing order for better routing results. Additionally, we propose a fault-tolerant structure as an option for users, which only occupies little area around control channels, and significantly improves the reliability against blockage defects. Experimental results demonstrate that the proposed methodology can efficiently connect all microvalves to user-specified boundaries, significantly reduce control port usage, shorten control channels, and improve reliability compared to baseline methods.
publication: '*Proceedings of the 43rd IEEE/ACM International Conference on Computer-Aided Design*'
publication_short: '*ICCAD*'
doi: 10.1145/3676536.3676744
---

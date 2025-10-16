---
title: Partitioning-free 3D-IC Floorplanning

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Shuo Ren
- Zhen Zhuang
- admin
- Leilei Jin
- Libo Shen
- Bei Yu
- Tsung-Yi Ho

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-09-02'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-02T09:22:59.432201Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 31st Asia and South Pacific Design Automation Conference*'
publication_short: 'ASPDAC'

doi: ''

abstract: 'Although 3D IC integration offers a promising path to alleviate interconnect
  bottlenecks in 2D designs, efficient 3D floorplanning remains challenging due to
  its increased spatial complexity. Prior approaches that directly extend 2D representations
  into 3D suffer from exponential solution spaces, while pre-partitioning strategies
  constrain the global optimization landscape by fixing block-to-die assignments early.
  As a result, both approaches not only hinder comprehensive exploration of the 3D
  design space, but also overlook critical 3D, specific characteristics such as inter-die
  communication latency, which directly impact system performance but are often abstracted
  away in simplified 2D-extended models. To address these challenges, we propose Great3D,
  a partitioning-free 3D floorplanning framework that jointly optimizes block floorplan
  and die assignment without relying on predefined die partitioning. By a two-stage
  3D SDP optimization and 2D refinement, Great3D effectively minimizes wirelength
  and latency under outline constraints. Experimental results on GSRC benchmarks show
  that Great3D consistently achieves lower wirelength than the baselines, with up
  to 60% reduction on large-scale designs. Furthermore, the method maintains competitive
  runtime performance while demonstrating better scalability and robustness across
  diverse benchmark sizes. These results establish Great3D as a scalable and effective
  partitioning-free solution for high-quality 3D IC floorplanning. '

# Summary. An optional shortened abstract.
summary: ''

tags:
- 3D IC
- 3D Floorplanning
- Partitioning-free
- Semi-definite Programming

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
---

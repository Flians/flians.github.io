---
title: 'HeLO: A Heterogeneous Logic Optimization Framework by Hierarchical Clustering and Graph Learning'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yuan Pu
- Fangzhou Liu
- Zhuolun He
- Keren Zhu
- admin
- Ziyi Wang
- Tsung-Yi Ho
- Bei Yu

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-11-07'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-03-28T03:45:03.961632Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2025 International Symposium on Physical Design*'
publication_short: '*ISPD*'

doi: 10.1145/3698364.3705354

abstract: Modern very large-scale integration (VLSI) designs usually consist of modules
  with various topological structures and functionalities. To better optimize such
  large and heterogeneous logic networks, it is essential to identify the structural
  and functional characteristics of its modules, and represent them with appropriate
  DAG types (such as AIG, MIG, XAG, etc.) for logic optimization. This paper proposes
  HeLO, a hetero-DAG logic optimization framework empowered by hierarchical clustering
  and graph learning. HeLO leverages a hierarchical clustering algorithm, which splits
  the original Boolean network into sub-circuits by considering both topological and
  functional characteristics. A novel graph neural network model is customized to
  generate the topological-functional embedding (used for distance calculation in
  hierarchical clustering) and predict the best-fit DAG type of each sub-circuit.
  Experimental results demonstrate that HeLO outperforms LSOracle, the SOTA heterogeneous
  logic optimization framework, in terms of node-depth product (for technology-independent
  logic optimization) and delay-area product (for technology mapping) by 8.7% and
  6.9%, respectively.

# Summary. An optional shortened abstract.
summary: ''

tags:
- graph learning
- heterogeneous logic synthesis

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

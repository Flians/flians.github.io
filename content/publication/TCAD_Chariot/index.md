---
title: 'Compiler-Aware Heterogeneous Graph Learning for HLS QoR Prediction and Design Space Exploration'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Yanlong Huang
- Jierui Liu
- Yuhan She
- admin
- Hong Yan
- Tsung-Yi Ho
- Ray C.C. Cheung

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []
note: ''

date: '2026-09-03'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-09-03T08:08:14.594543Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '2'

# Publication name and optional abbreviated publication name.
publication: '*IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems*'
publication_short: '*TCAD*'

doi: '10.1109/TCAD.2026.3732102'

abstract: 'High-level synthesis (HLS) design space exploration seeks Pareto-optimal designs within vast directive configuration spaces. Existing graph neural network approaches rely mostly on single-graph, homogeneous-style representations that do not model pragma-to-target semantics explicitly, which is especially limiting for memory-related optimizations whose hardware effects are realized through compiler IR rather than source syntax. We propose Chariot, an end-to-end HLS optimization framework with a compiler-aware graph construction pipeline that uses LLVM static analysis and Use-Def tracking to link pragmas to their resolved targets across memory boundaries, and represents each design as a heterogeneous graph with distinct node and edge types and a dedicated directive-to-target relation. Built on a multi-suite dataset from an AST-based rules engine, Chariot attains strong post-implementation QoR prediction and improves DSE ranking quality on unseen benchmarks, improving average top-k ranking quality by 2.3–4.8× over the strongest prior baseline across ranking budgets while delivering orders-of-magnitude speedup over synthesis-in-the-loop exploration. The advantages carry over to an independent public HLS dataset on a different FPGA family, where Chariot again attains the lowest QoR prediction error across all targets, demonstrating cross-dataset and cross-device generalization.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

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


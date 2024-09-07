---
title: 'FlatDD: A High-Performance Quantum Circuit Simulator using Decision Diagram and Flat Array'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Shui Jiang
- admin
- Lukas Burgholzer
- Robert Wille
- Tsung-Yi Ho
- Tsung-Wei Huang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2024-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-09-07T00:12:15.586244Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 53rd International Conference on Parallel Processing*'
publication_short: ''

doi: 10.1145/3673038.3673073

abstract: Quantum circuit simulator (QCS) is essential for designing quantum algorithms
  because it assists researchers in understanding how quantum operations work without
  access to expensive quantum computers. Traditional array-based QCSs suffer from
  exponential time and memory complexities. To address this problem, Decision Diagram
  (DD) was introduced to compress simulation data by exploring the circuit regularity.
  However, for irregular circuit structures, DD-based simulation incurs significant
  runtime and memory overhead. To overcome this challenge, we present FlatDD, a high-performance
  QCS that capitalizes on the strength of both DD- and array-based approaches. FlatDD
  parallelizes the simulation workload at multiple levels and leverages an efficient
  caching technique to reuse historical results. To further enhance the simulation
  performance for deep circuits, FlatDD introduces a gate-fusion algorithm to reduce
  the computational cost. Compared to state-of-the-art QCSs on commonly used quantum
  circuits, FlatDD achieves 34.81× speed-up and 1.93× memory reduction.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Decision Diagram
- Exponentially Weighted Moving Average
- Quantum Circuit Simulation

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
links:
- name: URL
  url: https://doi.org/10.1145/3673038.3673073
---

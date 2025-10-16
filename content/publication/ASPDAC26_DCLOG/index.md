---
title: "DCLOG: Don't Cares-based Logic Optimization using Pre-training Graph Neural Networks"

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Libo Shen
- Ziyi Wang
- Zhengxing Lei
- Zixiao Wang
- Junying Huang
- Bei Yu
- Tsung-Yi Ho

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-09-02'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-09-02T12:41:01.241158Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 31st Asia and South Pacific Design Automation Conference*'
publication_short: 'ASPDAC'

doi: ''

abstract: Logic rewriting serves as a robust optimization technique that enhances
  Boolean networks by substituting small segments with more effective implementations.
  The incorporation of don't cares in this process often yields superior optimization
  results. Nevertheless, the calculation of don't cares within a Boolean network can
  be resource-intensive. Therefore, it is crucial to develop effective strategies
  that mitigate the computational costs associated with don't cares while simultaneously
  facilitating the exploration of improved optimization outcomes. To address these
  challenges, this paper proposes DCLOG, a don't cares-based logic optimization framework,
  to efficiently and effectively optimize a given Boolean network. DCLOG leverages
  a pre-trained graph neural network model to filter out cuts without don't cares
  and then performs an incremental window simulation to calculate don't cares for
  each cut. Experimental results demonstrate the effectiveness and efficiency of DCLOG
  on large Boolean networks, specifically average size reductions of 15.64% and 1.44%
  while requiring less than 23.84% and 44.70% of the average runtime compared with
  state-of-the-art methods for the majority-inverter graph (MIG), respectively.

# Summary. An optional shortened abstract.
summary: ''

tags:
- logic optimization
- don't cares
- graph neural network
- majority-inverter graph

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


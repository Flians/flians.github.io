---
title: 'An Optimal DFF-Oriented Technology Legalization Algorithm for Rapid Single-Flux-Quantum Circuits'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Minglei Zhou
- admin
- Ran Zhang
- Xiaochun Ye
- Tsung-Yi Ho
- Junying Huang

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2025-04-30'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2025-04-30T05:18:25.155838Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the Great Lakes Symposium on VLSI*'
publication_short: '*GLSVLSI*'

doi: '10.1145/3716368.3735163'

abstract: Superconducting rapid single-flux-quantum (RSFQ) logic has garnered considerable
  attention as a prospective technology for future computing systems, thanks to its
  superior high-speed and low-power characteristics. However, conventional semiconductor
  logic synthesis tools can not guarantee the functional correctness of the generated
  RSFQ circuits. RSFQ circuits require DFF and splitter insertion to satisfy the path
  balancing requirement and the fanout limitation, thereby legitimizing the circuit
  design. Furthermore, DFFs and splitters inserted in RSFQ circuits introduce delays,
  occupy area, and substantially increase energy dissipation. To address this problem,
  this paper proposes an optimal DFF-oriented technology legalization algorithm. First,
  an integer linear programming algorithm is proposed for the logic level assignment
  to minimize the number of inserted DFFs. Then a splitter tree is constructed for
  each net of the circuit to minimize the timing discrepancies among the various fanouts.
  The experimental results on ISCAS’85 and EPFL benchmarks demonstrate the effectiveness
  and efficiency of our proposed algorithm compared with the state-of-the-art, particularly
  with significant advantages on large circuits.

# Summary. An optional shortened abstract.
summary: ''

tags:
- RSFQ
- Superconducting logic circuits
- DFF and splitter insertion
- Integer linear programming

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: https://flians.github.io/pdf/JLS.pdf
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


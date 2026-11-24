---
title: 'ReSynP3D: Bridging Logic Resynthesis and Tier Repartitioning during 3D IC Placement Optimization'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Shuo Ren
- Shixi Chen
- Yaohui Han
- Fangzhou Liu
- Mingjun Li
- Libo Shen
- Xuanqi Chen
- admin
- Bei Yu
- Tsung-Yi Ho

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []
note: 'Corresponding Author'

date: '2026-11-18'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-11-18T10:32:05.779005Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the Design, Automation & Test in Europe Conference & Exhibition*'
publication_short: 'DATE'

doi: ''

abstract: "As Moore's law slows, 3D ICs offer a promising path to continued improvements in performance and energy efficiency. In 3D ICs, Boolean structure and tier assignment jointly determine critical-path delay, yet fixing the logic structure before placement leaves cross-tier restructuring opportunities unexplored. We present ReSynP3D, a timing-driven cross-tier logic resynthesis method integrated into placement iterations. It restructures critical combinational regions across dies using Boolean transformations and timing-aware technology mapping under placement-derived boundary timing and load constraints. Internal cross-tier connections can change while the region's input--output functionality is preserved. A measured cross-tier delay penalty guides resynthesis, and criticality-weighted local tier repartitioning assigns the replacement cells to the two tiers. Together, these steps target cell delay and tier crossings, with power, performance, and area (PPA) evaluated after routing. Across the 16 reported cases on eight designs and two technology nodes, ReSynP3D improves WNS-derived post-route frequency by 9.1\% on average and up to 34.2\% over Pin-3D."

# Summary. An optional shortened abstract.
summary: ''

tags:
- Logic synthesis; logic rewriting; 3D IC

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

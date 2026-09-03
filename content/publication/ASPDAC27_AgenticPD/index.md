---
title: 'AgenticPD: A Stage-Aware Agentic Framework for Closed-Loop Physical Design Optimization'

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Shuo Ren
- Zijin Cheng
- Yaohui Han
- Libo Shen
- Leilei Jin
- Wanting Tian
- admin
- Chao Wang 
- Bei Yu 
- Tsung-Yi Ho

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2026-09-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2026-09-01T09:22:59.432201Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- '1'

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 32nd Asia and South Pacific Design Automation Conference*'
publication_short: 'ASPDAC'

doi: ''

abstract: 'Physical design quality-of-results~(QoR) optimization is hard and expensive. Choices made at one stage can help or hurt later stages. Each evaluation requires a costly EDA run through the full flow. While existing methods still treat optimization as flat parameter tuning or a LLM-based script generation task, we present AgenticPD\footnote{Our code is open-sourced at \url{https://anonymous.4open.science/r/AgenticPD-C74B}. $^*$~Corresponding author: Rongliang Fu (rlfu@cse.cuhk.edu.hk).}, a stage-aware agentic framework for physical design QoR optimization. Instead of re-running the full flow after every trial, AgenticPD is organized around the stage boundaries of the physical design flow, where a Judge Agent navigates the search and stage-specialized agents make local decisions within their own stage using stage-local tools. Additionally, the agent harness in AgenticPD provides structured observations, execution history, and agent context management. Together, these components form a stage-aware closed loop: measured post-GR QoR updates the optimization history, the Judge selects a retained design state and the stages to revise, and the Stage Agents execute the resulting downstream branch; post-DR QoR is reserved for final reporting. AgenticPD improves timing while maintaining competitive power and area.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Physical Design
- LLM
- Agent

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

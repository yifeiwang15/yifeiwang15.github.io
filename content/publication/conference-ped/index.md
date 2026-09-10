---
title: 'Advancing Ligand-based Virtual Screening and Molecular Generation with Pretrained Molecular Embedding Distance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shiyun Wa
  - admin
  - Simone Sciabola
  - Ye Wang

# Author notes (optional)


date: '2026-04-27'
doi: '10.48550/arXiv.2604.24474'



# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "International Conference on Machine Learning Workshop on AI for Science (ICML 2026 AI4Science)"
publication_short: ICML 2026 Workshop

abstract: "Molecular similarity plays a central role in ligand-based drug discovery, such as virtual screening, analog searching, and goal-directed molecular generation. However, traditional similarity measures, ranging from fingerprint-based Tanimoto coefficients to 3D shape overlays, are often computationally expensive at scale or rely on hand-crafted molecular descriptors. Meanwhile, many deep learning approaches to similarity-aware design still depend on similarity-specific supervision or costly data curation, limiting their generality across targets. In this work, we propose pretrained embedding distance (PED) as an effective alternative, computed directly from pretrained molecular models without task-specific training. Experimental results show that PED exhibits distinct correlations with traditional similarity metrics, and performs effectively in both ranking molecules for virtual screening and guiding molecular generation via reward design. These findings suggest that pretrained molecular embeddings capture rich structural information and can serve as a promising and scalable similarity measurement for modern AI-aided drug discovery."

# Summary. An optional shortened abstract.
summary: "We propose pretrained embedding distance (PED), a molecular similarity measure computed directly from pretrained models without task-specific training, effective for both ranking molecules in virtual screening and guiding molecular generation via reward design."

tags:
  - AI For Drug Discovery
  - Virtual Screening
  - Molecular Representation Learning
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2604.24474'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

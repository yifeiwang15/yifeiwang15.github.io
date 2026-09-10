---
title: 'Elite-Weighted Supervised Fine-tuning for Goal-Directed Molecular Optimization'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Shiyun Wa
  - admin
  - Anna G. Green
  - Simone Sciabola
  - Ye Wang

# Author notes (optional)


date: '2026-08-31'
doi: '10.48550/arXiv.2609.00189'



# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: arXiv
publication_short: arXiv

abstract: "Goal-directed optimization is essential for steering molecular generators to propose candidates with desired properties. However, it is often implemented with policy-gradient reinforcement learning, which requires a generation-trajectory log-probability whose form depends on the model architecture and generation procedure. This makes an optimizer difficult to reuse across architectures and conditional generative designs. Supervised fine-tuning needs none of that machinery, but its update is driven by a fixed dataset, so the reward never enters the update. We introduce Elite-Weighted Supervised Fine-tuning (EW-SFT), which uses reward to guide elite selection of high-scoring molecules, and updates the model by its own pretraining loss on that set. Ablations show that reward information is passed primarily through elite selection, rather than through continuous weighting within the selected set. Because the update consumes only scored molecules and the model's native loss, the same rule applies across autoregressive, masked-diffusion, and discrete-flow generators, and across de novo, motif-extension, and linker-design tasks. Under a fixed budget of 3D shape alignment oracle calls on two kinase reference compounds, EW-SFT consistently outperforms the corresponding native optimizers. It further improves goal-directed optimization under a 2D similarity oracle on four held-out references and achieves comparable performance on a sample-efficiency benchmark without a trajectory-level RL formulation. These results demonstrate that EW-SFT is a unified and effective optimizer across molecular generators, design constraints, references, and oracles."

# Summary. An optional shortened abstract.
summary: "We introduce Elite-Weighted Supervised Fine-tuning (EW-SFT), which passes reward through elite selection and updates the model with its own pretraining loss, yielding a single optimizer that transfers across autoregressive, masked-diffusion, and discrete-flow molecular generators."

tags:
  - AI For Drug Discovery
  - Generative AI
  - Molecular Optimization
# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2609.00189'
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

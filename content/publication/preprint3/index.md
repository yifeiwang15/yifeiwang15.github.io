---
title: "Counterpart Fairness--Addressing Systematic between-group Differences in Fairness Evaluation"
authors:
- admin
- Zhengyang Zhou
- Liqin Wang
- John Laurentiev
- Peter Hou
- Li Zhou
- Pengyu Hong

# author_notes: "Equal contribution."


date: "2023-09-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: 'When using machine learning (ML) to aid decision-making, it is critical to ensure that an algorithmic decision is fair and does not discriminate against specific individuals/groups, particularly those from underprivileged populations. Existing group fairness methods aim to ensure equal outcomes (such as loan approval rates) across groups delineated by protected variables like race or gender. However, these methods overlook the intricate, inherent differences among these groups that could influence outcomes. The confounding factors, which are non-protected variables but manifest systematic differences, can significantly affect fairness evaluation. Therefore, we recommend a more refined and comprehensive approach that accounts for both the systematic differences within groups and the multifaceted, intertwined confounding effects. We proposed a fairness metric based on counterparts (i.e., individuals who are similar with respect to the task of interest) from different groups, whose group identities cannot be distinguished algorithmically by exploring confounding factors. We developed a propensity-score-based method for identifying counterparts, avoiding the issue of comparing "oranges" with "apples". In addition, we introduced a counterpart-based statistical fairness index, called Counterpart-Fairness (CFair), to assess the fairness of ML models. Various empirical studies were conducted to validate the effectiveness of CFair.'

# Summary. An optional shortened abstract.
summary: 'We analyzed the impact of systematic differences and biases in data collection on group fairness assessment and accordingly proposed a counterpart-based fairness evaluation index.'

tags:
- Fairness
- Confounding Issue
- Systematic Differences

featured: false
links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/pdf/2305.18160'
url_code: 'https://github.com/zhengyjo/CFair'
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
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

---
title: "Motif-based graph representation learning with application to chemical molecules"
authors:
- admin
- Shiyang Chen
- Guobin Chen
- Ethan Shurberg
- Hang Liu
- Pengyu Hong
author_notes: ""

date: "2023-01-11"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-11T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Informatics"
publication_short: "Informatics"

abstract: "This work considers the task of representation learning on the attributed relational graph (ARG). Both the nodes and edges in an ARG are associated with attributes/features allowing ARGs to encode rich structural information widely observed in real applications. Existing graph neural networks offer limited ability to capture complex interactions within local structural contexts, which hinders them from taking advantage of the expression power of ARGs. We propose motif convolution module (MCM), a new motif-based graph representation learning technique to better utilize local structural information. The ability to handle continuous edge and node features is one of MCM’s advantages over existing motif-based models. MCM builds a motif vocabulary in an unsupervised way and deploys a novel motif convolution operation to extract the local structural context of individual nodes, which is then used to learn higher level node representations via multilayer perceptron and/or message passing in graph neural networks. When compared with other graph learning approaches to classifying synthetic graphs, our approach is substantially better at capturing structural context. We also demonstrate the performance and explainability advantages of our approach by applying it to several molecular benchmarks."

# Summary. An optional shortened abstract.
summary: "We designed a novel convolution module for graph representational learning on molecules with an efficient pretraining strategy, enabling the capture of local structural and semantic information from graph motifs."

tags:
- Graph Neural Network
- Molecular Learning
- Interpretability
- Motif-based Pretraining
featured: false
# links:
# - name: ""
#   url: ""
url_pdf: 'https://www.mdpi.com/2227-9709/10/1/8'
url_code: 'https://github.com/yifeiwang15/MotifConv'
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/14f0ji8Gc_3Hl2h0Qn2SvP5sEJNanAyWT/view?usp=sharing'
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
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

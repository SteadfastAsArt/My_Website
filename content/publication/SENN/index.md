---
title: "SENN: Learning Subgraph Prediction via Seq-to-seq Model"
authors:
- C. Chen
- Anzhou Li
- Yubo Tao
date: "2019-08-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-08-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Networks in real world scenarios are often large and time-consuming for current learning methods. In order to address this problem, we propose a transformer-based model for subgraph relevant tasks in dynamic networks. The proposed method is an end-to-end model to learn a mapping from the subgraph structure in the current snapshot to the subgraph structure in the next snapshot directly, i.e., the edge existence among multiple nodes in the subgraph. The model can be iteratively updated via adjacent snapshots in chronological order to learn the evolution of subgraphs in dynamic networks. We compare our model with several SOTA methods by subgraph prediction and subgraph pattern prediction tasks in multiple real-world homogenous and heterogeneous dynamic networks respectively. The results demonstrate that our model generally has better performance in these two tasks, a rise from 1.99% to 14.65%.

# Summary. An optional shortened abstract.
summary: An end-to-end transformer-based model was proposed to make subgraph relevant tasks more accurate and efficient, which could be extensively applied to real world scenarios.

tags:
- Representation Learning
featured: false

# links:
# - name: Custom Link
#   url:  '#'
# url_pdf: '#'
url_code: 'https://github.com/cad420/SENN-Subgraph-Prediction-Method'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
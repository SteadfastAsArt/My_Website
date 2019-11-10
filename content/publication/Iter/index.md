---
title: "Guided Negative Sampling for Incrementally Learning Dynamic Network Embeddings"
authors:
- C. Chen
- Anzhou Li
- Yubo Tao
date: "2019-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-02-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Random walk based network embedding methods have shown good performance in network analysis, and most of them use negative sampling based on a pre-defined node degree distribution, which has the popular neighbor problem. When extending these static methods to dynamic networks, we not only need to preserve the proximity between nodes and temporal continuity of embeddings, but also support to learn new snapshots incrementally. In this paper, we propose a novel framework by systematically considering the characteristics of dynamic networks for incremental embedding learning. The previous embedding is first used to initialize the current embedding, and positive samples can be generated from added edges to update the embedding incrementally. We further propose a guided negative sampling strategy based on the deleted structure/edges and previous embedding to obtain real and effective negative samples. Finally, we design a simple but effective method for initializing new nodes to generate negative samples for them. We applied two representative static methods for evaluation and the experiments show that our method generally outperforms other SOTA methods in the link prediction and network reconstruction. We also apply our method on anomaly detection to verify the effectiveness in the real-world application.

# Summary. An optional shortened abstract.
summary: An end-to-end transformer-based model was proposed to make subgraph relevant tasks more accurate and efficient, which could be extensively applied to real world scenarios.

tags:
- Representation Learning
featured: false

# links:
# - name: Custom Link
#   url:  '#'
# url_pdf: '#'
# url_code: '#'
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
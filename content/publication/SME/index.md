---
title: "Scalable Node Embedding based on Network Simplification"
authors:
- Anzhou Li
- C. Chen
- Yubo Tao
date: "2019-06-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-06-05T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Most node embedding methods learn on the node level directly, which could be time-consuming for large networks. There are various motifs in the network, such as stars and connectors. The representations of nodes in the motif exist specific relationships, as demonstrated in our empirical study. In this paper, we propose a general framework for node embeddings based on network simplification to accelerate network representation learning and improve the quality of node embeddings. We identify several specific motifs and simplify them as the anchor-spanner architecture. After learning node embeddings on the simplified network, we propose the corresponding methods to reconstruct the node embeddings of spanners. Our framework can be integrated with most node embedding methods. The experiments demonstrate that our framework can reduce the training time with average of 20%-50% and improve the accuracy of the network reconstruction task up to 40% compared to node embeddings trained on the original networks.

# Summary. An optional shortened abstract.
summary: We proposed a general framework based on motif simplification to improve the efficiency and effectiveness of network representation learning.

tags:
- Source Themes
featured: false

# links:
# - name: Custom Link
#   url:  '#'
# url_pdf: '#'
url_code: 'https://github.com/SteadfastAsArt/SME'
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
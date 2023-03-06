---
title: "Exploiting Asymmetric Errors for LDPC Decoding Optimization on 3D NAND Flash Memory"
authors:
- Qiao Li
- Liang Shi
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2020-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Computers (TC),2020"
publication_short: "*TC 2020*"

abstract: By stacking layers vertically, the adoption of 3D NAND has significantly increased the capacity for storage systems. The complex structure of 3D NAND introduces more errors than planer flash. To address the reliability issue, low-density parity-check (LDPC) code with a strong error correction capability is now widely applied on 3D NAND flash memory. However, LDPC has long decoding latency when the raw bit error rates (RBER) are high. This is because it needs fine-grained soft sensing between voltage states to iteratively decode the raw data. Multiple sensing voltages are applied on flash cell array to gain necessary information for decoding. In this article, a new sensing level placement scheme with reduced number of sensing levels is proposed. The basic idea for the placement scheme is motivated by three asymmetric error characteristics of flash memory:the asymmetric errors between different states, the asymmetric errors caused by voltage left-shifts and right-shifts and asymmetric errors among layers in a 3D NAND flash block. With awareness of these three types of error characteristics, reduced number of sensing levels are placed to achieve reduced read latency for LDPC decoding while maintaining the error correction capability of LDPC. Experiment analysis shows that the proposed scheme achieves significant performance improvement.

# Summary. An optional shortened abstract.
summary: In this work, three asymmetric error characteristics are studied on flash memory.Motivated by these characteristics, three asymmetric sensing level placement schemes are proposed to place just enough number of sensing levels between the adjacent voltage state pairs.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: uploads/TC2020.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

---
title: "Sentinel Cells Enabled Fast Read for NAND Flash"
authors:
- Qiao Li
- Min Ye
# Author notes (optional)
author_notes:
  - '1'
  - 
date: "2019-04-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "11th USENIX Workshop on Hot Topics in Storage and File Systems"
publication_short: "*HotStorage 2019*"

abstract: With the increasing bit density and adoption of 3D NAND, flash memory suffers from increased errors. To address the issue, flash devices adopt error correction codes (ECC) with strong error correction capability, like low-density parity-check (LDPC) code, to correct errors. The drawback of LDPC is that, to correct data with a high raw bit error rate (RBER), read latency will be amplified. This work proposes to address this issue with the assistance of approximate data. First, studies have been conducted and show there are ample amount of approximate data available in flash storage. Second, a novel data organization is proposed to fortify the reliability of regular data by leaving approximate data unprotected. Finally, a new data allocation strategy and modified garbage collection scheme are presented to complete the design. The experimental results show that the proposed approach can improve read performance by 30% on average comparing to current techniques.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: uploads/Hotstorage2019.pdf
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

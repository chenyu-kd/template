---
title: 'Shaving Retries with Sentinels for Fast Read over High-Density 3D Flash'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Qiao Li
  - Min Ye

# Author notes (optional)
author_notes:
  - '1'
  - 

date: '2020-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 53rd Annual IEEE/ACM International Symposium on Microarchitecture 
publication_short: '*MICRO 2020*'

abstract: High-density flash-memory chips are under tremendous demands with the exponential growth of data. At the same time, the slow read performance of these high-density flashmemory chips becomes a new challenge. In this work, we analyze the high raw bit error rates (RBER) issue by characterizing the error behaviours of 3D QLC flash-memory chips. A preferred read voltage to a QLC cell could vary among layers and might even change in a short period of time due to the temperature. A sentinel-cell approach is thus proposed to utilize the error characteristics among cells. We propose to infer the optimal read voltages of a wordline based on errors introduced on sentinel cells. An on-line calibration procedure is further presented to resolve the problem of possible non-uniform error distribution on some wordlines. With optimal voltages being inferred, the number of read retries will be significantly reduced. Experiments show that optimal read voltages can be instantly obtained in 94% cases on average over the evaluated QLC flash memory with at most 2 read retries, and with merely 0.2% space overheads for adopting sentinel cells. The number of read retries could be reduced by 82% on average, and the read performance can be improved by 74% on average through a series of extensive experiments over 3D TLC and QLC flash-memory chips.

# Summary. An optional shortened abstract.
summary: we reserve a subset of cells as sentinel cells on each wordline and select one read voltage as the sentinel voltage.

tags: []

# Display this page in the Featured widget?
featured: false



url_pdf: uploads/Micro2020.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: #'
url_slides: '#'
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).

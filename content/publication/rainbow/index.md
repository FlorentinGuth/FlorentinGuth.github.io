---
title: 'A rainbow in deep network black boxes'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Brice Ménard
  - Gaspar Rochette
  - Stéphane Mallat

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: ArXiv
publication_short: ArXiv

abstract: What do neural networks learn? A major difficulty is that every training run results in a _different set of weights_ but nevertheless leads to _the same performance_. We introduce a model of the probability distribution of these weights. Layers are _not_ independent, but their dependencies can be captured by an alignment procedure. We use this model to show that **networks learn the same features no matter their initialization**. We also compress trained weights to a reduced set of summary statistics, from which a family of networks with equivalent performance can be reconstructed.

# Summary. An optional shortened abstract.
summary: We show how deep network weights can be compressed to a reduced set of _summary statistics_ (the learned "features") that _(i)_ **all networks share no matter their initialization** and _(ii)_ that allow **regenerating weights with an equivalent performance**.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Tutorial
  url: https://bonnerlab.github.io/ccn-tutorial/pages/analyzing_neural_networks.html
- name: Summary
  url: https://openreview.net/pdf?id=ofEBFOrITI

url_pdf: 'https://arxiv.org/pdf/2305.18512.pdf'
url_code: 'https://github.com/FlorentinGuth/Rainbow'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'poster.pdf'
# url_project: ''
url_slides: 'slides.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
url_video: 'https://www.youtube.com/live/BZ34XH4ffEc?si=i3dy6irauWE__O2b&t=23897'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  placement: 1
  focal_point: 'TopLeft'
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

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

Resources:
- [Original paper](https://arxiv.org/pdf/2305.18512.pdf) (with the mathematical model)
- [Video](https://www.youtube.com/watch?v=3s5Q4Vk9SlE) of my talk at the AI and Pure Maths conference of IMSA (maths audience)
- [Video](https://www.youtube.com/watch?v=tcCKRQ8hEEk) of my talk at Youth in High Dimensions 2024 (ML/physics audience)
- [Video](https://www.youtube.com/live/BZ34XH4ffEc?si=i3dy6irauWE__O2b&t=23897) of my talk at DeepMath 2023 (ML/maths audience)
- [Keynote](https://www.youtube.com/watch?v=6cxX6M5VFYE&t=632s) at the CCN 2023 conference with Mick Bonner (neuro/cogsci audience)
- [Tutorial](https://bonnerlab.github.io/ccn-tutorial/pages/analyzing_neural_networks.html) to reproduce some of our results in a simplified setting
- **New:** [Shorter paper](https://openreview.net/pdf?id=ofEBFOrITI) (summary of ideas and application to comparisons across training datasets)

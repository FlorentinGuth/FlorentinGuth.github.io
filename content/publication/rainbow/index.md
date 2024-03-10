---
title: 'A Rainbow in Deep Network Black Boxes'

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
summary: We show how deep network weights can be compressed to a reduced set of summary statistics ("_the learned features_") that _(i)_ **all networks share no matter their initialization** and _(ii)_ that allow **regenerat weights with an equivalent performance**.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2305.18512.pdf'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
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
  placement: 3
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

Check out the [video](https://www.youtube.com/live/BZ34XH4ffEc?si=i3dy6irauWE__O2b&t=23897) of my talk at DeepMath 2023, or our [keynote](https://www.youtube.com/watch?v=6cxX6M5VFYE&t=632s) <!-- and [tutorial] --> at the CCN 2023 conference with Mick Bonner and his lab!

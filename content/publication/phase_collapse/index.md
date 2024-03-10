---
title: 'Phase Collapse in Neural Networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - John Zarka
  - Stéphane Mallat

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2021-10-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Conference on Learning Representations, 2022
publication_short: ICLR 2022

abstract: "What is the role of the non-linearity in deep networks? In image classification, it was shown that it leads to a _neural collapse_, where images from the same class are all mapped to the same representation. There have been two main theories, one based on sparsity assumptions (using soft-thresoldings) and one based on symmetry groups (using complex moduli). We show that the mechanism at play in deep networks is the latter, and introduce the _phase collapse_ operation which is **both necessary and sufficient** to reach high classification accuracies. It leads to a **simplified architecture without learned biases nor spatial filters** that is mathematically easier to reason about, while preserving performance."

# Summary. An optional shortened abstract.
summary: We show that deep networks rely on _phase collapses_ to classify images, **rather than sparse coding** as assumed in previous works, and introduce **a simplified architecture with minimal learning** while maintaining high accuracy.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2110.05283.pdf'
url_code: 'https://github.com/FlorentinGuth/PhaseCollapse'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'poster.pdf'
# url_project: ''
url_slides: 'slides.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://iclr.cc/virtual/2022/poster/6415'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  placement: 1
  focal_point: 'Top'
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


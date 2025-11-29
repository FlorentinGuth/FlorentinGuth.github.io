---
title: 'Learning normalized image densities via dual score matching'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Zahra Kadkhodaie
  - Eero P Simoncelli

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-05-30T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Conference on Neural Information Processing Systems, 2025
publication_short: NeurIPS 2025

abstract: "Learning probability models from data is at the heart of many learning tasks. We introduce a new framework for learning normalized energy (log probability) models inspired from diffusion generative models. The energy model is fitted to data by two “score matching” objectives: the first constrains the gradient of the energy (the “score”, as in diffusion models), while the second constrains its *time derivative* along the diffusion. We validate the approach on both synthetic and natural image data: in particular, we show that the estimated log probabilities do not depend on the specific images used during training. Finally, we demonstrate that both image probability and local dimensionality vary significantly with image content, challenging simple interpretations of the manifold hypothesis."

# Summary. An optional shortened abstract.
summary: We show how to estimate *normalized* probabilities by modifying the objective and architecture of diffusion models, and report several surprising observations on the properties of the learned probabilistic model.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2506.05310'
url_code: 'https://github.com/FlorentinGuth/DualScoreMatching'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
url_poster: 'poster.pdf'
# url_project: ''
url_slides: 'slides.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://www.youtube.com/live/BZ34XH4ffEc?si=i3dy6irauWE__O2b&t=23897'

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

+++
title = "Revisiting Softmax for Uncertainty Approximation in Text Classification"
date = 2023-06-19T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Andreas Nugaard Holm", "Dustin Wright", "Isabelle Augenstein"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Information"
publication_short = "In *Information*"

# Abstract and optional shortened version.
abstract = "Uncertainty approximation in text classification is an important area with applications in domain adaptation and interpretability. One of the most widely used uncertainty approximation methods is Monte Carlo (MC) Dropout, which is computationally expensive as it requires multiple forward passes through the model. A cheaper alternative is to simply use the softmax based on a single forward pass without dropout to estimate model uncertainty. However, prior work has indicated that these predictions tend to be overconfident. In this paper, we perform a thorough empirical analysis of these methods on five datasets with two base neural architectures in order to identify the trade-offs between the two. We compare both softmax and an efficient version of MC Dropout on their uncertainty approximations and downstream text classification performance, while weighing their runtime (cost) against performance (benefit). We find that, while MC dropout produces the best uncertainty approximations, using a simple softmax leads to competitive and in some cases better uncertainty estimation for text classification at a much lower computational cost, suggesting that softmax can in fact be a sufficient uncertainty estimate when computational resources are a concern."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["limited-data"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/abs/2210.14037"
url_preprint = ""
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
preview_only = true

  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



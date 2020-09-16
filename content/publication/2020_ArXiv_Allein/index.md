+++
title = "Time-Aware Evidence Ranking for Fact-Checking"
date = 2020-09-13T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Liesbeth Allein", "Isabelle Augenstein", "Marie-Francine Moens"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["3"]

# Publication name and optional abbreviated version.
publication = "CoRR, abs/2004.14283."
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Truth can vary over time. Therefore, fact-checking decisions on claim veracity should take into account temporal information of both the claim and supporting or refuting evidence. Automatic fact-checking models typically take claims and evidence pages as input, and previous work has shown that weighing or ranking these evidence pages by their relevance to the claim is useful. However, the temporal information of the evidence pages is not generally considered when defining evidence relevance. In this work, we investigate the hypothesis that the timestamp of an evidence page is crucial to how it should be ranked for a given claim. We delineate four temporal ranking methods that constrain evidence ranking differently: evidence-based recency, claim-based recency, claim-centered closeness and evidence-centered clustering ranking. Subsequently, we simulate hypothesis-specific evidence rankings given the evidence timestamps as gold standard. Evidence ranking is then optimized using a learning to rank loss function. The best performing time-aware fact-checking model outperforms its baseline by up to 33.34%, depending on the domain. Overall, evidence-based recency and evidence-centered clustering ranking lead to the best results. Our study reveals that time-aware evidence ranking not only surpasses relevance assumptions based purely on semantic similarity or position in a search results list, but also improves veracity predictions of time-sensitive claims in particular. "
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["fact-checking"]

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
url_pdf = "https://arxiv.org/abs/2009.06402"
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
  caption = "Share of evidence with retrievable timestamps"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



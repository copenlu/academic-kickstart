+++
title = "Multi-Hop Fact Checking of Political Claims"
date = 2020-09-13T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wojciech Ostrowski", "Arnav Arora", "Pepa Atanasova", "Isabelle Augenstein"]

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
publication = "CoRR, abs/´2009.06401"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Recently, novel multi-hop models and datasets have been introduced to achievemore complex natural language reasoning with neural networks. One notable taskthat requires multi-hop reasoning is fact checking, where a chain of connectedevidence pieces leads to the final verdict of a claim. However, existingdatasets do not provide annotations for the gold evidence pieces, which is acritical aspect for improving the explainability of fact checking systems. Theonly exception is the FEVER dataset, which is artificially constructed based onWikipedia and does not use naturally occurring political claims and evidencepages, which is more challenging. Most claims in FEVER only have one evidencesentence associated with them and require no reasoning to make labelpredictions -- the small number of instances with two evidence sentences onlyrequire simple reasoning. In this paper, we study how to perform more complexclaim verification on naturally occurring claims with multiple hops overevidence chunks. We first construct a small annotated dataset, PolitiHop, ofreasoning chains for claim verification. We then compare the dataset to otherexisting multi-hop datasets and study how to transfer knowledge from moreextensive in- and out-of-domain resources to PolitiHop. We find that the taskis complex, and achieve the best performance using an architecture thatspecifically models reasoning over evidence chains in combination within-domain transfer learning."
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
url_pdf = "https://arxiv.org/abs/2009.06401"
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
  caption = "An illustration of multiple hops over an instance of the PolitiHop dataset"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



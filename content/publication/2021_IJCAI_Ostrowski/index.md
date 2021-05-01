+++
title = "Multi-Hop Fact Checking of Political Claims"
date = 2021-04-30T00:00:00
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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "In Proceedings of the 30th International Joint Conference on Artificial Intelligence"
publication_short = "In *IJCAI*"

# Abstract and optional shortened version.
abstract = "Recently, novel multi-hop models and datasets have been introduced to achieve more complex natural language reasoning with neural networks. One notable task that requires multi-hop reasoning is fact checking, where a chain of connected evidence pieces leads to the final verdict of a claim. However, existing datasets do not provide annotations for the gold evidence pieces, which is a critical aspect for improving the explainability of fact checking systems. The only exception is the FEVER dataset, which is artificially constructed based on Wikipedia and does not use naturally occurring political claims and evidence pages, which is more challenging. Most claims in FEVER only have one evidence sentence associated with them and require no reasoning to make label predictions -- the small number of instances with two evidence sentences only require simple reasoning. In this paper, we study how to perform more complex claim verification on naturally occurring claims with multiple hops overevidence chunks. We first construct a small annotated dataset, PolitiHop, of reasoning chains for claim verification. We then compare the dataset to other existing multi-hop datasets and study how to transfer knowledge from more extensive in- and out-of-domain resources to PolitiHop. We find that the task is complex, and achieve the best performance using an architecture that specifically models reasoning over evidence chains in combination within-domain transfer learning."
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
url_code = "https://github.com/copenlu/politihop"
url_dataset = "https://github.com/copenlu/politihop"
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



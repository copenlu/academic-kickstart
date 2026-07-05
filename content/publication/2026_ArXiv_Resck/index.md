+++
title = "Mitigating Cross-Lingual Cultural Inconsistencies in LLMs via Consensus-Driven Preference Optimisation"
date = 2026-05-27T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lucas Resck", "Isabelle Augenstein", "Anna Korhonen"]

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
publication = "CoRR, abs/2605.12515"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Despite their impressive capabilities, multilingual large language models (MLLMs) frequently exhibit inconsistent behaviour when the prompt's language changes. While such adaptation is generally desirable, it becomes a critical failure when a user's identity is explicitly defined. For instance, given a fixed British persona and an ambiguous everyday knowledge query about literature, the prompt's language frequently overwrites the system persona -- yielding Shakespeare in English but Cervantes in Spanish. To robustly quantify this Cross-lingual Cultural Inconsistency, we introduce Singleton Fleiss's κS, a metric mathematically resilient to hallucinations. For mitigation, we propose Cross-lingual Cultural Consistent Preference Optimisation (C-3PO), a consensus-driven alignment framework. C-3PO achieves up to a 0.13-point absolute increase in κS over unaligned models, consistently outperforming strong prompting and representation steering baselines whilst preserving explicit user identities, cultural neutrality and intrinsic cultural knowledge. Empirical evaluations demonstrate this inconsistency disproportionately affects lower-resource languages like Indonesian and Persian. Finally, early decoding of intermediate layers reveals that MLLMs implicitly personalise outputs towards the prompt language's stereotypical culture as forward-pass representations stabilise."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = [""]

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
url_pdf = "https://arxiv.org/abs/2605.12515"
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



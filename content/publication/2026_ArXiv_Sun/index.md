+++
title = "Investigating the Interplay between Contextual and Parametric Chain-of-Thought Faithfulness under Optimization"
date = 2026-05-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jingyi Sun", "Qianli Wang", "Pepa Atanasova", "Nils Feldhus", "Isabelle Augenstein"]

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
publication = "CoRR, abs/2605.24960"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Chain-of-Thought (CoT) faithfulness, i.e., whether CoTs genuinely reflect large language models' (LLM) underlying behavior, is typically evaluated under two disjoint paradigms: contextual faithfulness, measured by perturbing the input or CoT trace, and parametric faithfulness, assessed by intervening on a model's parametric knowledge. Yet prior work compares them only descriptively. We fill this gap by proposing FaithMate, a unified preference-alignment interface for optimizing models towards either faithfulness paradigm. It enables us to investigate the interplay between the two paradigms, examining whether and to what extent faithfulness gains generalize within and across paradigms. Across three models, two datasets, and six faithfulness metrics, we find that the two paradigms are positively coupled, yet asymmetric: optimizing towards parametric faithfulness yields consistent gains across both paradigms, whereas the contextual counterpart delivers more variable gains. Within the contextual paradigm, faithfulness gains on one metric do not consistently transfer to others, implying that existing contextual metrics capture disjoint facets of faithfulness and exposing inherent trade-offs. These findings imply that CoT faithfulness is not a monolithic objective and therefore requires multifaceted optimization and evaluation."
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
url_pdf = "https://arxiv.org/abs/2605.24960"
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



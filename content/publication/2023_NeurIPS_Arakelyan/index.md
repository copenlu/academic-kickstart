+++
title = "Adapting Neural Link Predictors for Complex Query Answering"
date = 2023-09-21T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Erik Arakelyan", "Pasquale Minervini", "Isabelle Augenstein"]

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
publication = "2023 Conference on Neural Information Processing Systems"
publication_short = "In *NeurIPS 2023*"

# Abstract and optional shortened version.
abstract = "Answering complex queries on incomplete knowledge graphs is a challenging task where a model needs to answer complex logical queries in the presence of missing knowledge. Recently, Arakelyan et al. (2021); Minervini et al. (2022) showed that neural link predictors could also be used for answering complex queries: their Continuous Query Decomposition (CQD) method works by decomposing complex queries into atomic sub-queries, answers them using neural link predictors and aggregates their scores via t-norms for ranking the answers to each complex query. However, CQD does not handle negations and only uses the training signal from atomic training queries: neural link prediction scores are not calibrated to interact together via fuzzy logic t-norms during complex query answering. In this work, we propose to address this problem by training a parameter-efficient score adaptation model to re-calibrate neural link prediction scores: this new component is trained on complex queries by back-propagating through the complex query-answering process. Our method, CQDA, produces significantly more accurate results than current state-of-the-art methods, improving from 34.4 to 35.1 Mean Reciprocal Rank values averaged across all datasets and query types while using ≤35% of the available training query types. We further show that CQDA is data-efficient, achieving competitive results with only 1% of the training data, and robust in out-of-domain evaluations."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["knowledge-bases", "question-answering", "explainability"]

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
url_pdf = "https://arxiv.org/abs/2301.12313"
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



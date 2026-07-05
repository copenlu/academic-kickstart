+++
title = "Understanding helpfulness and harmless tension in reward models"
date = 2026-06-11T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Eshaan Tanwar", "Pepa Atanasova"]

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
publication = "CoRR, abs/2606.13209"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Reward models are a key component of reinforcement learning from human feedback (RLHF), aligning language models toward both helpful and harmless behaviour. However, the internal mechanisms underlying these objectives and their conflicts remain poorly understood. We study alignment tension in reward models trained under helpfulness-only, harmlessness-only, and mixed-objective settings. We find that mixed-objective models often underperform single-objective models, indicating interference between objectives. Using activation-based methods, we identify neurons associated with each objective and study their functional roles via targeted ablations. We find that these neurons causally support their corresponding objectives while often negatively affecting the opposing one. We find that a substantial proportion of neurons are shared between helpfulness and harmlessness, and that these shared neurons exert a disproportionate influence on model behaviour, contributing to alignment tension. Additionally, our results provide insights and mechanistic interpretation into how alignment objectives are represented in reward models and why multi-objective alignment remains challenging, motivating future work on disentangled and controllable alignment methods."
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
url_pdf = "https://arxiv.org/abs/2606.13209"
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



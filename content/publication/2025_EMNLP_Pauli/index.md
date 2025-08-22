+++
title = "A Meta-Evaluation of Style and Attribute Transfer Metrics"
date = 2025-08-21T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Amalie Brogaard Pauli", "Isabelle Augenstein", "Ira Assent"]

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
publication = "In Findings of the 2025 Conference on Empirical Methods in Natural Language Processing (EMNLP 2025)"
publication_short = "In *EMNLP*"

# Abstract and optional shortened version.
abstract = "LLMs make it easy to rewrite text in any style, be it more polite, persuasive, or more positive. We present a large-scale study of evaluation metrics for style and attribute transfer with a focus on content preservation; meaning content not attributed to the style shift is preserved. The de facto evaluation approach uses lexical or semantic similarity metrics often between source sentences and rewrites. While these metrics are not designed to distinguish between style or content differences, empirical meta-evaluation shows a reasonable correlation to human judgment. In fact, recent works find that LLMs prompted as evaluators are only comparable to semantic similarity metrics, even though intuitively, the LLM approach should better fit the task. To investigate this discrepancy, we benchmark 8 metrics for evaluating content preservation on existing datasets and additionally construct a new test set that better aligns with the meta-evaluation aim. Indeed, we then find that the empirical conclusion aligns with the intuition: content preservation metrics for style/attribute transfer must be conditional on the style shift. To support this, we propose a new efficient zero-shot evaluation method using the likelihood of the next token. We hope our meta-evaluation can foster more research on evaluating content preservation metrics, and also to ensure fair evaluation of methods for conducting style transfer."
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
url_pdf = "https://arxiv.org/abs/2502.15022"
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



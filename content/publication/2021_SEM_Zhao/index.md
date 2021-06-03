+++
title = "Inducing Language-Agnostic Multilingual Representations"
date = 2021-05-29T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wei Zhao", "Steffen Eger", "Johannes Bjerva", "Isabelle Augenstein"]

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
publication = "In Proceedings of the 10th Joint Conference on Lexical and Computational Semantics (*SEM)"
publication_short = "In **SEM*"

# Abstract and optional shortened version.
abstract = "Cross-lingual representations have the potential to make NLP techniques available to the vast majority of languages in the world. However, they currently require large pretraining corpora, or assume access to typologically similar languages. In this work, we address these obstacles by removing language identity signals from multilingual embeddings. We examine three approaches for this: (i) re-aligning the vector spaces of target languages (all together) to a pivot source language; (ii) removing languages-specific means and variances, which yields better discriminativeness of embeddings as a by-product; and (iii) normalizing input texts by removing morphological contractions and sentence reordering, thus yielding language-agnostic representations. We evaluate on the tasks of XNLI and reference-free MT evaluation across 19 selected languages. Our experiments demonstrate the language agnostic behavior of our multilingual representations, allowing better zero-shot cross-lingual transfer to distant and low-resource languages, and decrease the performance gap by 8.9 points (M-BERT) and 18.2 points (XLM-R) on average across all tasks and languages. We particularly show that vector normalization can lead to more consistent gains and is complementary to input normalization and recently popular vector space re-alignment. We make our codes and models available."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["limited-data", "multilingual-learning"]

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
url_pdf = "https://arxiv.org/abs/2008.09112"
url_preprint = ""
url_code = "https://github.com/AIPHES/Language-Agnostic-Contextualized-Encoders"
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
  caption = "XNLI and RFEval performance for different language similarities to English"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



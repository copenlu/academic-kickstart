+++
title = "Unsupervised Evaluation for Question Answering with Transformers"
date = 2020-09-13T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lukas Muttenthaler", "Isabelle Augenstein", "Johannes Bjerva"]

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
publication = "In Proceedings of the 3rd Workshop on Analyzing and interpreting neural networks for NLP (BlackboxNLP at EMNLP)"
publication_short = "In *BlackboxNLP at EMNLP*"

# Abstract and optional shortened version.
abstract = "It is challenging to automatically evaluate the answer of a QA model at inference time. Although many models provide confidence scores, and simple heuristics can go a long way towards indicating answer correctness, such measures are heavily dataset-dependent and are unlikely to generalise. In this work, we begin by investigating the hidden representations of questions, answers, and contexts in transformer-based QA architectures. We observe a consistent pattern in the answer representations, which we show can be used to automatically evaluate whether or not a predicted answer span is correct. Our method does not require any labelled data and outperforms strong heuristic baselines, across 2 datasets and 7 domains. We are able to predict whether or not a model's answer is correct with 91.37% accuracy on SQuAD, and 80.7% accuracy on SubjQA. We expect that this method will have broad applications, e.g., in semi-automatic development of QA datasets."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["question-answering"]

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
url_pdf = ""
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
  caption = "Probability Density Function of the cosine similarities among tokens w.r.t.  the true answer spanin SQuAD. Correct answer predictions (blue) tend tohave higher cosine similarities than wrong answer pre-dictions (orange)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



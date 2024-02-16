+++
title = "A Primer on Contrastive Pretraining in Language Processing: Methods, Lessons Learned and Perspectives"
date = 2022-09-07T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nils Rethmeier", "Isabelle Augenstein"]

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
publication = "ACM Computing Surveys"
publication_short = "In *CSUR*"

# Abstract and optional shortened version.
abstract = "Modern natural language processing (NLP) methods employ self-supervised pretraining objectives such as masked language modeling to boost the performance of various downstream tasks. These pretraining methods are frequently extended with recurrence, adversarial, or linguistic property masking. Recently, contrastive self-supervised training objectives have enabled successes in image representation pretraining by learning to contrast input-input pairs of augmented images as either similar or dissimilar. In NLP however, a single token augmentation can invert the meaning of a sentence during input-input contrastive learning, which led to input-output contrastive approaches that avoid the issue by instead contrasting over input-label pairs. In this primer, we summarize recent self-supervised and supervised contrastive NLP pretraining methods and describe where they are used to improve language modeling, zero to few-shot learning, pretraining data-efficiency, and specific NLP tasks. We overview key contrastive learning concepts with lessons learned from prior research and structure works by applications. Finally, we point to open challenges and future directions for contrastive NLP to encourage bringing contrastive NLP pretraining closer to recent successes in image representation pretraining."
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
url_pdf = "https://dl.acm.org/doi/10.1145/3561970"
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
  caption = "Contrastive input-output (X, Y) pretraining"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



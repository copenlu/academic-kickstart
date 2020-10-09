+++
title = "Claim Check-Worthiness Detection as Positive Unlabelled Learning"
date = 2020-09-14T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Dustin Wright", "Isabelle Augenstein"]

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
publication = "In Findings of the 2020 Conference on Empirical Methods in Natural Language Processing (EMNLP)"
publication_short = "In *EMNLP*"

# Abstract and optional shortened version.
abstract = "A critical component of automatically combating misinformation is the detection of fact check-worthiness, i.e. determining if a piece of information should be checked for veracity. There are multiple isolated lines of research which address this core issue: check-worthiness detection from political speeches and debates, rumour detection on Twitter, and citation needed detection from Wikipedia. What is still lacking is a structured comparison of these variants of check-worthiness, as well as a unified approach to them. We find that check-worthiness detection is a very challenging task in any domain, because it both hinges upon detecting how factual a sentence is, and how likely a sentence is to be believed without verification. As such, annotators often only mark those instances they judge to be clear-cut check-worthy. Our best-performing method automatically corrects for this, using a variant of positive unlabelled learning, which learns when an instance annotated as not check-worthy should in fact have been annotated as being check-worthy. In applying this, we outperform the state of the art in two of the three domains studied for check-worthiness detection in English."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["limited-data", "fact-checking"]

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
url_pdf = "http://arxiv.org/abs/2003.02736"
url_preprint = ""
url_code = "https://github.com/copenlu/check-worthiness-pu-learning"
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



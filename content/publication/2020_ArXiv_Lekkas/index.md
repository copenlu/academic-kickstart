+++
title = "Multi-Sense Language Modelling"
date = 2020-12-11T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Andrea Lekkas", "Peter Schneider-Kamp", "Isabelle Augenstein"]

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
publication = "CoRR, abs/2012.05776"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "The effectiveness of a language model is influenced by its token representations, which must encode contextual information and handle the same word form having a plurality of meanings (polysemy). Currently, none of the common language modelling architectures explicitly model polysemy. We propose a language model which not only predicts the next word, but also its sense in context. We argue that this higher prediction granularity may be useful for end tasks such as assistive writing, and allow for more a precise linking of language models with knowledge bases. We find that multi-sense language modelling requires architectures that go beyond standard language models, and here propose a structured prediction framework that decomposes the task into a word followed by a sense prediction task. For sense prediction, we utilise a Graph Attention Network, which encodes definitions and example uses of word senses. Overall, we find that multi-sense language modelling is a highly challenging task, and suggest that future work focus on the creation of more annotated training datasets."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["multilingual-learning"]

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
url_pdf = "https://arxiv.org/abs/2012.05776"
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
  caption = "Part of the dictionary graph for the word “bank”"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



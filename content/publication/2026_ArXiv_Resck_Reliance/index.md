+++
title = "The Reliance Hypothesis: Chain-of-Thought Faithfulness Rises as Language Resource Level Falls"
date = 2026-10-16T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lucas Resck", "Jingyi Sun", "Qianli Wang", "Isabelle Augenstein", "Anna Korhonen"]

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
publication = "CoRR, abs/2610.22841"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Chain-of-Thought (CoT) faithfulness matters for monitoring, explaining and safely deploying large language models, yet it has been studied mostly in English. Languages differ in level, the amount of text available to learn from, so models know less in lower-resource languages, which may change how much they rely on their reasoning. To our knowledge, we are the first to relate CoT faithfulness to both resource level and task type (knowledge- or reasoning-intensive). On parallel multiple-choice questions from Multilingual Massive Multitask Language Understanding (MMMLU) in eight languages, faithfulness rises as resource level falls on knowledge-intensive tasks but not on reasoning-intensive ones, a gap that points the same way across four models and several faithfulness measures. We propose, and find support for, the Reliance Hypothesis: models rely more on their reasoning when they cannot recall the answer, as in lower-resource languages on knowledge-intensive tasks. Model confidence partly explains the effect of resource level, but not the knowledge-reasoning gap. Languages in which models are less confident rely more on reasoning, yet less confident answers within a language do not, a Simpson's paradox. In lower-resource languages, models rely on their reasoning for more answers, not more strongly for each. CoT monitoring may therefore be most informative in lower-resource languages, where it is least often validated."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["explainability", "multilingual-learning"]

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
url_pdf = "https://arxiv.org/abs/2610.22841"
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



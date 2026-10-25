+++
title = "Shaping the Document, Not the Model: Optimized Suffixes for Context Following"
date = 2026-10-19T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Bao Dinh", "Sekh Mainul Islam", "Masahiro Kaneko", "Timothy Baldwin", "Isabelle Augenstein"]

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
publication = "CoRR, abs/2610.26236"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "When a user supplies a document and wants the answer drawn from it, a language model is expected to follow it even when it contradicts its parametric knowledge. Prior work has focused on making the model rely on context by steering activations, contrasting logits during decoding, or instructing it in plain language. We ask whether the document alone, with no instruction written into it and no access to the model at inference time, is enough. We optimize a document suffix by discrete token search, starting from the answer to a single question and extending the objective to a set of passages, to multi-hop questions that follow from the planted fact, and to later turns of a conversation. On counterfactual passages that contradict parametric knowledge of the model, the suffix flips nearly all items the model resists across three instruction-tuned model families, in most settings outperforms the decoding baseline and the strongest instruction we could write, and matches activation steering. Controls show that the suffix largely acts through the passage rather than injecting the answer, and a single suffix per model transfers to unseen passages. Each extended objective carries the effect to its target, so the objective, not only the document, sets how far the effect reaches."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["explainability", "fact-checking"]

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
url_pdf = "https://arxiv.org/abs/2610.26236"
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



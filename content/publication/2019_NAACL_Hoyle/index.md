+++
title = "Combining Disparate Sentiment Lexica with a Multi-View Variational Autoencoder"
date = 2019-02-22T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alexander Hoyle", "Lawrence Wolf-Sonkin", "Hanna Wallach", "Ryan Cotterell", "Isabelle Augenstein"]

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
publication = "In Proceedings of the *2019 Conference of the North American Chapter of the      Association for Computational Linguistics: Human Language Technologies*."
publication_short = "In *NAACL*"

# Abstract and optional shortened version.
abstract = "When assigning quantitative labels to a dataset, different methodologies may rely on different scales. One such example is sentiment lexica, which can use binary, categorical, or continuous scales to quantify word polarity. Of high interest is thus the ability to unify these scores to both achieve maximal coverage over words and account for potential imprecision, while retaining score interpretability. We introduce a generative model of sentiment to combine these scores into a common latent representation. We realise this model with a novel multi-view VAE, which encodes and decodes conditioned on the data source. To evaluate the expressivity of this metric against others, we induce heuristic sentence-level annotators with these lexica. While existing weakly-supervised methods improve coverage by defining features for each lexicon, our latent representation is low-dimensional and easily interpretable. In a downstream weak labelling setup, our model outperforms individual lexica as well as straightforward combinations thereof across several tasks."
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
  caption = "A depiction of the encoder portion of SentiVAE"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++



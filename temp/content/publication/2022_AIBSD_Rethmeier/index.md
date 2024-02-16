+++
title = "Contrastive Text Pretraining for Zero to Few-Shot Long-Tail Learning"
date = 2021-11-29T00:00:00
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
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "AAAI 2022 Workshop on Artificial Intelligence with Biased or Scarce Data (AIBSD 2022)"
publication_short = "In *AIBSD 2022*"

# Abstract and optional shortened version.
abstract = "For natural language processing (NLP) tasks such as sentiment or topic classification, currently prevailing approaches heavily rely on pretraining large self-supervised models on massive external data resources.  However, this methodology is being critiqued for: exceptional compute and pretraining data requirements; diminishing returns on both large and small datasets; and importantly, favourable evaluation settings that overestimate performance differences. The core belief behind current methodology, coined 'the bitter lesson' by R. Sutton, is that 'compute scale-up beats data and compute-efficient algorithms', neglecting that progress in compute hardware scale-up is based almost entirely on the miniaturisation of resource consumption. We thus approach pretraining from a miniaturisation perspective, such as not to require massive external data sources and models, or learned translations from continuous input embeddings to discrete labels.  To minimise overly favourable evaluation, we examine learning on a long-tailed, low-resource, multi-label text classification dataset with noisy, highly sparse labels and many rare concepts. To this end, we propose a novel 'dataset-internal' contrastive autoencoding approach to self-supervised pretraining and demonstrate marked improvements in zero-shot, few-shot and solely supervised learning performance; even under an unfavorable low-resource scenario, and without defaulting to large-scale external datasets for self-supervision. We also find empirical evidence that zero and few-shot learning markedly benefit from adding more `dataset-internal', self-supervised training signals, which is of practical importance when retrieving or computing on large external sources of such signals is infeasible."
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
url_pdf = "https://arxiv.org/abs/2010.01061"
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
  caption = "Contrastive  text-sequence-embedding-2-label-embedding  matcher  model"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



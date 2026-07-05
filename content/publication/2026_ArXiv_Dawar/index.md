+++
title = "Do We Still Need Humans in the Loop? Comparing Human and LLM Annotation in Active Learning for Hostility Detection"
date = 2026-06-17T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Ahmad Dawar Hakimi", "Lea Hirlimann", "Isabelle Augenstein", "Hinrich Schütze"]

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
publication = "CoRR, abs/2604.13899"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Instruction-tuned LLMs can annotate thousands of instances at low cost. This raises two questions for active learning (AL): can LLM labels replace human labels within the AL loop, and does AL remain necessary when entire corpora can be cheaply labeled? We investigate both on a new dataset of 277,902 German political TikTok comments (25,974 LLM-labeled, 5,000 human-annotated), comparing LLM and human annotation across seven conditions, four encoders, and 10 random seeds. Under a two-question interface that mirrors the human annotation task, LLM annotation at scale outperforms human-supervised classifiers at roughly one-tenth the cost ($28 for GPT-5.2 Batch API vs. $316 for Prolific). The advantage holds for both a closed-source (GPT-5.2) and an open-weight (Qwen3.5-122B-10B) LLM, is robust under soft-label evaluation, and is unlocked specifically by the two-question decomposition; a holistic single-prompt baseline only ties with human supervision. AL provides no reliable advantage over random sampling under either LLM annotator. However, error structure varies sharply: only GPT-5.2 under the two-question interface produces classifiers with near-human FP/FN balance, while other LLM variants over-flag border-control and economic competition discourse. We release the dataset and code."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = [""]

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
url_pdf = "https://arxiv.org/abs/2604.13899"
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



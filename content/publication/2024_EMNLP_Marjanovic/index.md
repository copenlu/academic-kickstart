+++
title = "DYNAMICQA: Tracing Internal Knowledge Conflicts in Language Models"
date = 2024-09-24T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sara Vera Marjanović", "Haeun Yu", "Pepa Atanasova", "Maria Maistro", "Christina Lioma", "Isabelle Augenstein"]

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
publication = "In Findings of the 2024 Conference on Empirical Methods in Natural Language Processing (EMNLP 2024)"
publication_short = "In *EMNLP*"

# Abstract and optional shortened version.
abstract = "Knowledge-intensive language understanding tasks require Language Models (LMs) to integrate relevant context, mitigating their inherent weaknesses, such as incomplete or outdated knowledge. However, conflicting knowledge can be present in the LM's parameters, termed intra-memory conflict, which can affect a model's propensity to accept contextual knowledge. To study the effect of intra-memory conflict on an LM's ability to accept relevant context, we utilize two knowledge conflict measures and a novel dataset containing inherently conflicting data, DynamicQA. This dataset includes facts with a temporal dynamic nature where facts can change over time and disputable dynamic facts, which can change depending on the viewpoint. DynamicQA is the first to include real-world knowledge conflicts and provide context to study the link between the different types of knowledge conflicts. We also evaluate several measures on their ability to reflect the presence of intra-memory conflict: semantic entropy and a novel coherent persuasion score. With our extensive experiments, we verify that LMs exhibit a greater degree of intra-memory conflict with dynamic facts compared to facts that have a single truth value. Furthermore, we reveal that facts with intra-memory conflict are harder to update with context, suggesting that retrieval-augmented generation will struggle with the most commonly adapted facts."
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
url_pdf = "https://arxiv.org/abs/2407.17023"
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



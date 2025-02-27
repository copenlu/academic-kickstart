+++
title = "Measuring Gender Bias in West Slavic Language Models"
date = 2023-05-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Sandra Martinková", "Karolina Stańczak", "Isabelle Augenstein"]

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
publication = "In Proceedings of the 9th Workshop on Slavic Natural Language Processing 2023 (SlavicNLP 2023)"
publication_short = "In *SlavicNLP*"

# Abstract and optional shortened version.
abstract = "Pre-trained language models have been known to perpetuate biases from the underlying datasets to downstream tasks. However, these findings are predominantly based on monolingual language models for English, whereas there are few investigative studies of biases encoded in language models for languages beyond English. In this paper, we fill this gap by analysing gender bias in West Slavic language models. We introduce the first template-based dataset in Czech, Polish, and Slovak for measuring gender bias towards male, female and non-binary subjects. We complete the sentences using both mono- and multilingual language models and assess their suitability for the masked language modelling objective. Next, we measure gender bias encoded in West Slavic language models by quantifying the toxicity and genderness of the generated words. We find that these language models produce hurtful completions that depend on the subject’s gender. Perhaps surprisingly, Czech, Slovak, and Polish language models produce more hurtful completions with men as subjects, which, upon inspection, we find is due to completions being related to violence, death, and sickness."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["bias-detection", "multilingual-learning"]

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
url_pdf = "https://aclanthology.org/2023.bsnlp-1.17/"
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
  caption = "Multilingual completions for the m-BERT and XLM-R language models"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Center"
+++



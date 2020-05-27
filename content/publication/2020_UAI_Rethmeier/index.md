+++
title = "TX-Ray: Quantifying and Explaining Model-Knowledge Transfer in (Un-)Supervised NLP"
date = 2020-05-20T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Nils Rethmeier", "Vageesh Kumar Saxena", "Isabelle Augenstein"]

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
publication = "In Proceedings of the *Conference on Uncertainty in Artificial Intelligence*"
publication_short = "In *UAI*"

# Abstract and optional shortened version.
abstract = "While state-of-the-art NLP explainability (XAI) methods focus on supervised, per-instance end or diagnostic probing task evaluation[4, 2, 10], this is insufficient to interpret and quantify model knowledge transfer during (un-) supervised training. By instead expressing each neuron as an interpretable token-activation distribution collected over many instances, one can quantify and guide visual exploration of neuron-knowledge change between model training stages to analyze transfer beyond probing tasks and the per-instance level. This allows one to analyze: (RQ1) how neurons abstract knowledge during unsupervised pretraining; (RQ2) how pretrained neurons zero-shot transfer knowledge to new domain data; and (RQ3) how supervised tasks reorder pretrained neuron knowledge abstractions. Since the meaningfulness of XAI methods is hard to quantify [11, 4], we analyze three example learning setups (RQ1-3) to empirically verify that our method (TX-Ray): identifies transfer (ir-)relevant neurons for pruning (RQ3), and that its transfer metrics coincide with traditional measures like perplexity (RQ1). We also find, that TX-Ray guided pruning of supervision (ir-)relevant neuron-knowledge (RQ3) can identify `lottery ticket'-like [9, 40] neurons that drive model performance and robustness. Upon inspecting pruned neurons, we find that task-relevant neuron-knowledge (`tickets'), appear (over-)fit, while task-irrelevant neurons lower overfitting, i.e. TX-Ray identifies neurons that generalize, transfer or specialize model-knowledge [25]. Finally, through RQ1-3, we find that TX-Ray helps to explore and quantify dynamics of (continual) knowledge transfer and that it can shed light on neuron-knowledge specialization and generalization, to complement (costly) supervised probing task procurement and established `summary' statistics like perplexity, ROC or F scores."
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
url_pdf = "http://arxiv.org/abs/1912.00982"
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



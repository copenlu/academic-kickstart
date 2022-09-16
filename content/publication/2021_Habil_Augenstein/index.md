+++
title = "Towards Explainable Fact Checking"
date = 2021-01-05T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Isabelle Augenstein"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["5"]

# Publication name and optional abbreviated version.
publication = "Thesis presented to the University of Copenhagen Faculty of Science in partial fulfillment of the requirements for the degree of Doctor Scientiarum (Dr. Scient.)"
publication_short = "*Dr. Scient. thesis*"

# Abstract and optional shortened version.
abstract = "The past decade has seen a substantial rise in the amount of mis- and disinformation online, from targeted disinformation campaigns to influence politics, to the unintentional spreading of misinformation about public health. This development has spurred research in the area of automatic fact checking, from approaches to detect check-worthy claims and determining the stance of tweets towards claims, to methods to determine the veracity of claims given evidence documents. These automatic methods are often content-based, using natural language processing methods, which in turn utilise deep neural networks to learn higher-order features from text in order to make predictions. As deep neural networks are black-box models, their inner workings cannot be easily explained. At the same time, it is desirable to explain how they arrive at certain decisions, especially if they are to be used for decision making. While this has been known for some time, the issues this raises have been exacerbated by models increasing in size, and by EU legislation requiring models to be used for decision making to provide explanations, and, very recently, by legislation requiring online platforms operating in the EU to provide transparent reporting on their services. Despite this, current solutions for explainability are still lacking in the area of fact checking. A further general requirement of such deep learning based method is that they require large amounts of in-domain training data to produce reliable explanations. As automatic fact checking is a very recently introduced research area, there are few sufficiently large datasets. As such, research on how to learn from limited amounts of training data, such as how to adapt to unseen domains, is needed. This thesis presents my research on automatic fact checking, including claim check-worthiness detection, stance detection and veracity prediction. Its contributions go beyond fact checking, with the thesis proposing more general machine learning solutions for natural language processing in the area of learning with limited labelled data. Finally, the thesis presents some first solutions for explainable fact checking. Even so, the contributions presented here are only a start on the journey towards what is possible and needed. Future research should focus on more holistic explanations by combining instance- and model-based approaches, by developing large datasets for training models to generate explanations, and by collective intelligence and active learning approaches for using explainable fact checking models to support decision making."
abstract_short = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["fact-checking", "explainability"]

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
url_pdf = "http://isabelleaugenstein.github.io/papers/Isabelle_Doktordisputats.pdf"
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



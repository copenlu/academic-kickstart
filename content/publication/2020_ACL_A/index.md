+++
title = "2kenize: Tying Subword Sequences for Chinese Script Conversion"
date = 2020-04-03T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Pranav A", "Isabelle Augenstein"]

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
publication = "In Proceedings of the 2020 Annual Conference of the Association for Computational Linguistics (ACL)"
publication_short = "In *ACL*"

# Abstract and optional shortened version.
abstract = "Simplified Chinese to Traditional Chinese script conversion is a common preprocessing step in Chinese NLP. Despite this, current approaches have poor performance because they do not take into account that a simplified Chinese character can correspond to multiple traditional characters. Here, we propose a novel model that can disambiguate between mappings and convert between the two scripts. The model is based on subword segmentation, two language models, as well as a method for mapping between subword sequences. We further construct benchmark datasets for topic classification and script conversion. Our proposed method outperforms previous Chinese Character Conversion approaches by 6 points in accuracy. These results are further confirmed in a downstream application, where 2kenize is used to preprocess text for topic classification. An error analysis reveals that our method's particular strengths are in dealing with code mixing and named entities."
abstract_short = "We propose a novel Chinese character conversion model that can disambiguate between mappings and convert between the two scripts. The model is based on subword segmentation, two language models, as well as a method for mapping between subword sequences."

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
url_pdf = "http://isabelleaugenstein.github.io/papers/ACL2020_2kenize.pdf"
url_preprint = ""
url_code = ""
url_dataset = "https://github.com/pranav-ust/2kenize"
url_project = ""
url_slides = ""
url_video = "http://slideslive.com/38928985"
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
  caption = "From the given SC sentence, we create possible TC sequences using mappings. We input these to Viterbi, which recursively calls LSTM. Viterbi outputs the mapping sequence. We perform beam search to find the best TC sequence from the mapping sequence."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++



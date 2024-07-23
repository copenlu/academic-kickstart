+++
title = "Measuring and Benchmarking Large Language Models' Capabilities to Generate Persuasive Language"
date = 2024-06-21T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Amalie Brogaard Pauli", "Isabelle Augenstein", "Ira Assent"]

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
publication = "CoRR, abs/2406.17753"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "We are exposed to much information trying to influence us, such as teaser messages, debates, politically framed news, and propaganda - all of which use persuasive language. With the recent interest in Large Language Models (LLMs), we study the ability of LLMs to produce persuasive text. As opposed to prior work which focuses on particular domains or types of persuasion, we conduct a general study across various domains to measure and benchmark to what degree LLMs produce persuasive text - both when explicitly instructed to rewrite text to be more or less persuasive and when only instructed to paraphrase. To this end, we construct a new dataset, Persuasive-Pairs, of pairs each consisting of a short text and of a text rewritten by an LLM to amplify or diminish persuasive language. We multi-annotate the pairs on a relative scale for persuasive language. This data is not only a valuable resource in itself, but we also show that it can be used to train a regression model to predict a score of persuasive language between text pairs. This model can score and benchmark new LLMs across domains, thereby facilitating the comparison of different LLMs. Finally, we discuss effects observed for different system prompts. Notably, we find that different 'personas' in the system prompt of LLaMA3 change the persuasive language in the text substantially, even when only instructed to paraphrase. These findings underscore the importance of investigating persuasive language in LLM generated text."
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
url_pdf = "https://arxiv.org/abs/2406.17753"
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



+++
title = "Expanding Computation Spaces of LLMs at Inference Time"
date = 2025-09-29T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Yoonna Jang", "Kisu Yang", "Isabelle Augenstein"]

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
publication = "CoRR, abs/2509.24884"
publication_short = "In *CoRR*"

# Abstract and optional shortened version.
abstract = "Chain-of-thought (CoT) rationale enables language models to use additional task-related text for problem-solving, benefiting not only from detailed reasoning steps but also from the expanded computational space of longer inputs. Prior work has trained filler or special tokens to serve as additional computation spaces. In this study, we investigate whether language models can leverage artificially inserted sequences of filler tokens solely at inference. We first identify effective token types, numbers, and insertion locations, then examine at what stage of training models begin to exploit the expanded computation space, and finally analyze dynamics within these spaces via attention maps. Experiments on models ranging from 1.7B to 32B across open-domain QA and math tasks show that appropriate token types and counts vary, but placing filler tokens directly before the final 'Answer:' token is most effective. Smaller models benefit most, up to 12.372 percentage points in SmolLM2-1.7B-Instruct, indicating that these spaces act as additional computational capacity rather than redundant input. Attention maps reveal that expanded spaces often continue the original attention mechanism and sometimes focus on questions or answer options, suggesting meaningful computation for problem-solving."
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
url_pdf = "https://arxiv.org/abs/2509.24884"
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



+++
title = "On the Strengths of Pure Evolutionary Algorithms in Generating Adversarial Examples"
date = 2023-01-01T17:56:40+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Antony Bartlett", "Cynthia C. S. Liem", "Annibale Panichella"]

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
summary = "" 

# Publication name and optional abbreviated version.
publication = "The 16th Intl. Workshop on Search-Based and Fuzz Testing (SBFT)"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Deep learning (DL) models are known to be highly accurate, yet vulnerable to adversarial examples. While earlier research focused on generating adversarial examples using whitebox strategies, later research focused on black-box strategies, as models often are not accessible to external attackers. Prior studies showed that black-box approaches based on approximate gradient descent algorithms combined with meta-heuristic search (i.e., the BMI-FGSM algorithm) outperform previously proposed white- and black-box strategies. In this paper, we propose a novel black-box approach purely based on differential evolution (DE), i.e., without using any gradient approximation method. In particular, we propose two variants of a customized DE with customized variation operators: (1) a single-objective (Pixel-SOO) variant generating attacks that fool DL models, and (2) a multi-objective variant (Pixel-MOO) that also minimizes the number of changes in generated attacks. Our preliminary study on five canonical image classification models shows that Pixel-SOO and Pixel-MOO are more effective than the state-of-the-art BMI-FGSM in generating adversarial attacks. Furthermore, Pixel-SOO is faster than Pixel-MOO, while the latter produces subtler attacks than its single-objective variant."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["", ""]

# Links (optional).
url_pdf = ""
url_preprint = ""
url_code = "https://zenodo.org/record/7741267#.ZBRMCC-B3kI"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

+++
title = "Grammar-Based Evolutionary Fuzzing for JSON-RPC APIs"
date = 2023-01-01T17:56:40+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lisette Veldkamp", "Mitchell Olsthoorn", "Annibale Panichella"]

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
abstract = "Web Application Programming Interfaces (APIs) allow systems to be addressed programmatically and form the backbone of the internet. RESTful and RPC APIs are among the most common API architectures used. In the last decades, researchers have proposed various techniques for automated testing of RESTful APIs, however, to the best of the authors' knowledge there exists no work on testing JSON-RPC (one of the two data formats supported by RPC) APIs. To address this limitation, we propose a grammar-based evolutionary fuzzing approach for testing JSON-RPC APIs that uses a novel black-box heuristics. Specifically, we use a diversity-based fitness function based on hierarchical clustering to quantify the differences in API method responses. Our hypothesis is that responses that are unlike previously seen ones are an indication that new uncovered code paths are reached. We evaluate our approach on the XRP ledger, a large-scale industrial blockchain system that uses JSON-RPC APIs. Our results show that the proposed approach performs significantly better than the baseline (grammar-based fuzzer) and covers an additional 240 branches."
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

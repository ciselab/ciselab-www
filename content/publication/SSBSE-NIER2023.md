+++
title = "Multi-objective Black-Box Test Case Prioritization Based on Wordnet Distances"
date = 2023-10-18T09:16:23+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Imara van Dinten","Andy Zaidman","Annibale Panichella"]

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
publication = "15th Symposium on Search-Based Software Engineering - New Idea and Emerging Results Track (SSBSE-NIER 2023)"
publication_short = ""

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["COSMOS"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Test Case Prioritization","Search-based Software Testing", "WordNet", "Natural Language Processing", "Multi-objective Optimization"]


# Links (optional).
url_pdf = "https://link.springer.com/chapter/10.1007/978-3-031-48796-5_7"
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
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++

# Abstract
Test case prioritization techniques have emerged as effective strategies to optimize this process and mitigate the regression testing costs. Commonly, black-box heuristics guide optimal test ordering, leveraging information retrieval (e.g., cosine distance) to measure the test case distance and sort them accordingly. However, a challenge arises when dealing with tests of varying granularity levels, as they may employ distinct vocabularies (e.g., name identifiers). In this paper, we propose to measure the distance between test cases based on the shortest path between their identifiers within the WordNet lexical database. This additional heuristic is combined with the traditional cosine distance to prioritize test cases in a multi-objective fashion. Our preliminary study conducted with two different Java projects shows that test cases prioritized with WordNet achieve larger fault detection capability (APFD) compared to the traditional cosine distance used in the literature.


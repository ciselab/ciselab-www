+++
title = "Generating Class-Level Integration Tests Using Call Site Information"
subtitle = ""
date = 2022-09-13T09:29:14+02:00
lastmod = 2022-09-13T09:29:14+02:00
featured = true
draft = false

summary = ""
authors = ["Pouria Derakhshanfar", "Xavier Devroey", "Annibale Panichella",  "Andy Zaidman", "Arie van Deursen"]
tags = ["Test Case Generation", "Fuzzing", "Search-based Software Engineering", "Cling", "Software Testing", "Many-objective Optimization"]

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
publication = "IEEE Transactions on Software Engineering (TSE 2022)"
publication_short = ""

# Abstract and optional shortened version.
abstract = ""
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

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/pdf/2001.04221.pdf"
url_code = "https://github.com/STAMP-project/Cling-application"
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

Abstract: Search-based approaches have been used in the literature to automate the process of creating unit test cases. However, related work has shown that generated tests with high code coverage could be ineffective, i.e., they may not detect all faults or kill all injected mutants. In this paper, we propose CLING, an integration-level test case generation approach that exploits how a pair of classes, the caller and the callee, interact with each other through method calls. In particular, CLING generates integration-level test cases that maximize the Coupled Branches Criterion (CBC). Coupled branches are pairs of branches containing a branch of the caller and a branch of the callee such that an integration test that exercises the former also exercises the latter. CBC is a novel integration-level coverage criterion, measuring the degree to which a test suite exercises the interactions between a caller and its callee classes. We implemented CLING and evaluated the approach on 140 pairs of classes from five different open-source Java projects. Our results show that (1) CLING generates test suites with high CBC coverage, thanks to the definition of the test suite generation as a many-objectives problem where each couple of branches is an independent objective; (2) such generated suites trigger different class interactions and can kill on average 7.7% (with a maximum of 50%) of mutants that are not detected by tests generated randomly or at the unit level; (3) CLING can detect integration faults coming from wrong assumptions about the usage of the callee class (25 for our subject systems) that remain undetected when using automatically generated random and unit-level test suites.
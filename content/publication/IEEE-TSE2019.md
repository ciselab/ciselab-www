+++
title = "Testing with Fewer Resources: An Adaptive Approach to Performance-Aware Test Case Generation"
date = 2019-10-09T09:51:33+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Giovanni Grano", "Christoph Laaber", "Annibale Panichella", "Sebastiano Panichella"]

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
publication = "IEEE Transactions on Software Engineering"
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

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Test Case Generation", "Evolutionary Testing", "Performance Testing", "Search-based Software Engineering"]

# Links (optional).
url_pdf = ""
url_preprint = "https://arxiv.org/abs/1907.08578"
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

Abstract: Automated test case generation is an effective technique to yield high-coverage test suites. 
While the majority of research effort has been devoted to satisfying coverage criteria, a recent trend emerged towards optimizing other non-coverage aspects.
In this regard, runtime and memory usage are two essential dimensions: less expensive tests reduce the resource demands for the generation process and later regression testing phases.
This study shows that performance-aware test case generation requires solving two main challenges:
providing a good approximation of resource usage with minimal overhead and  
avoiding detrimental effects on both final coverage and fault detection effectiveness. 
To tackle these challenges, we conceived a set of performance proxies -inspired by previous work on performance testing- that provide a reasonable estimation of the test execution costs (i.e., runtime and memory usage).
Thus, we propose an adaptive strategy, called aDynaMOSA, which leverages these proxies by extending DynaMOSA, a state-of-the-art evolutionary algorithm in unit testing.
Our empirical study -involving 110 non-trivial Java classes- reveals 
that our adaptive approach generates test suite with statistically significant improvements in runtime (-25\%) and heap memory consumption (-15\%) compared to DynaMOSA. Additionally, aDynaMOSA has comparable results to DynaMOSA over seven different coverage criteria and similar fault detection effectiveness.
Our empirical investigation also highlights that the usage of performance proxies (i.e., without the adaptiveness) is not sufficient to generate more performant test cases without compromising the overall coverage. 

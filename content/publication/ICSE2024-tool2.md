+++
title = "TestSpark: IntelliJ IDEA’s Ultimate Test Generation Companion"
date = 2024-01-01T19:37:11+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["A. Sapozhnikov", "M. Olsthoorn", "A. Panichella", "V.V. Kovalenko", "A. Panichella", "P. Derakhshanfar"]

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
publication = "45hth International Conference on Software Engineering - Tool Demo Track (ICSE-Demonstration 2024)"
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
tags = ["Test Case Generation", "Large Language Models", "Evolutionary Testing", "Intellij IDEA"]

# Links (optional).
url_pdf = ""
url_preprint = "https://pure.tudelft.nl/ws/portalfiles/portal/173593530/TestSpark.pdf"
url_code = "https://github.com/JetBrains-Research/TestSpark"
url_dataset = ""
url_project = ""
url_slides = ""
url_video = "https://youtu.be/0F4PrxWfiXo"
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
Abstract: 

Writing software tests is laborious and time-consuming. To address
this, prior studies introduced various automated test-generation
techniques. A well-explored research direction in this field is unit
test generation, wherein artificial intelligence (AI) techniques create
tests for a method/class under test. While many of these techniques
have primarily found applications in a research context, existing
tools (e.g., EvoSuite, Randoop, and AthenaTest) are not user-friendly
and are tailored to a single technique. This paper introduces Test-
Spark, a plugin for IntelliJ IDEA that enables users to generate unit
tests with only a few clicks directly within their Integrated De-
velopment Environment (IDE). Furthermore, TestSpark also allows
users to easily modify and run each generated test and integrate
them into the project workflow. TestSpark leverages the advances of
search-based test generation tools, and it introduces a technique to
generate unit tests using Large Language Models (LLMs) by creating
a feedback cycle between the IDE and the LLM. Since TestSpark is
an open-source (https://github.com/JetBrains-Research/TestSpark),
extendable, and well-documented tool, it is possible to add new test
generation methods into the plugin with the minimum effort. This
paper also explains our future studies related to TestSpark and our
preliminary results.

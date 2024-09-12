+++
title = "Effective and Efficient API Misuse Detection via Exception Propagation and Search-based Testing"
date = 2019-05-01T20:22:51+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Maria Kechagia", "Xavier Devroey", "Annibale Panichella", "Georgios Gousios", "Arie van Deursen"]

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
publication = "The ACM SIGSOFT International Symposium on Software Testing and Analysis"
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
tags = ["Search-based Software Engineering", "Software Testing", "Static Analysis"]

# Links (optional).
url_pdf = ""
url_preprint = "https://pure.tudelft.nl/portal/files/54238155/catcher.pdf"
url_code = "https://github.com/mkechagia/Catcher"
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
<b> Abstract </b>: Application Programming Interfaces (APIs)
typically come with (implicit) usage constraints.
The violations of these constraints (API misuses)
can lead to software crashes.
Even though there are several tools that
can detect API misuses,
most of them suffer from a very high rate of false positives.
We introduce Catcher, a novel API misuse detection approach
that combines static exception propagation analysis with automatic search-based test case
generation to effectively and efficiently pinpoint crash-prone API misuses
in client applications.
We validate Catcher against 21 Java applications,
targeting misuses of the Java platform's API.
Our results indicate that Catcher is able to generate
test cases that uncover 243 (unique) API misuses that result in
crashes.
Our empirical evaluation shows that Catcher can detect a large number of misuses (77 cases)
that would remain undetected by the traditional coverage-based test case generator EvoSuite.
Additionally, Catcher is on average eight times faster than EvoSuite
in generating test cases for the identified misuses.
Finally, we find that the majority of the exceptions triggered by Catcher
are unexpected to developers i.e., not only unhandled in the source code but also not listed in the documentation of the client applications.

+++
title = "An Improved Pareto Front Modeling Algorithm for Large-scale Many-Objective Optimization"
date = 2022-03-27T10:56:44+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Annibale Panichella"]

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
featured = true 
summary = "A key idea in many-objective optimization is to approximate the optimal Pareto front using a set of representative non-dominated solutions. The produced solution set should be close to the optimal front (convergence) and well-diversified (diversity). Recent studies have shown that measuring both convergence and diversity depends on the shape (or curvature) of the Pareto front. In recent years, researchers have proposed evolutionary algorithms that model the shape of the non-dominated front to define environmental selection strategies that adapt to the underlying geometry. This paper proposes a novel method for non-dominated front modeling using the Newton-Raphson iterative method for roots finding. Second, we compute the distance (diversity) between each pair of non-dominated solutions using geodesics, which are generalizations of the distance on Riemann manifolds (curved topological spaces). Thereafter, we have introduced an evolutionary algorithm within the Adaptive Geometry Estimation based MOEA (AGE-MOEA) framework, which we called AGE-MOEA-II. Computational experiments with 17 problems from the WFG and SMOP benchmarks show that AGE-MOEA-II outperforms its predecessor AGE-MOEA as well as other state-of-the-art many-objective algorithms, i.e., NSGA-III, MOEA/D, VaEA, and LMEA." 

# Publication name and optional abbreviated version.
publication = "The Genetic and Evolutionary Computation Conference (GECCO 2022)"
publication_short = ""

# Abstract and optional shortened version.
abstract = ""
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Many-objective Optimization" , "Numerical Problems", "Evolutionary Computation"]

# Links (optional).
url_pdf = ""
url_preprint = "https://pure.tudelft.nl/ws/portalfiles/portal/117513741/main.pdf"
url_code = "https://zenodo.org/record/6462859"
url_dataset = "https://github.com/BIMK/PlatEMO"
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

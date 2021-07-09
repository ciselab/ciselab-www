---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Crash Reproduction Using Helper Objectives"
subtitle: ""
summary: "Evolutionary-based crash reproduction techniques aid developers in their debugging practices by generating a test case that reproduces a crash given its stack trace. In these techniques, the search process is typically guided by a single search objective called Crash Distance. Previous studies have shown that current approaches could only reproduce a limited number of crashes due to a lack of diversity in the population during the search. In this study, we address this issue by applying Multi-Objectivization using Helper-Objectives (MO-HO) on crash reproduction. In particular, we add two helper-objectives to the Crash Distance to improve the diversity of the generated test cases and consequently enhance the guidance of the search process. We assessed MO-HO against the single-objective crash reproduction. Our results show that MO-HO can reproduce two additional crashes that were not previously reproducible by the single-objective approach."
authors:
  [
    "Pouria Derakhshanfar",
    "Xavier Devroey",
    "Annibale Panichella",
    "Andy Zaidman",
    "Arie van Deursen",
  ]
tags:
  [
    "crash replication",
    "test case generation",
    "software testing",
    "search-based software engineering",
  ]
categories: []
date: 2020-07-04T18:56:54+02:00
lastmod: 2020-07-04T18:56:54+02:00
featured: false
draft: false

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types: ["1"]
publication: "The Genetic and Evolutionary Computation Conference (GECCO)"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ["STAMP"]
---

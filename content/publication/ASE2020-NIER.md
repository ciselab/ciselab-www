---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Generating Highly-structured Input Data by Combining Search-based Testing and Grammar-based Fuzzing"
subtitle: ""
summary: "Software testing is an important and time-consuming task that is often done manually. In the last decades, researchers have come up with techniques to generate input data (e.g., fuzzing) and automate the process of generating test cases (e.g., search-based testing). However, these techniques are known to have their own limitations: search-based testing does not generate highly-structured data; grammar-based fuzzing does not generate test case structures. To address these limitations, we combine these two techniques. By applying grammar-based mutations to the input data gathered by the search-based testing algorithm, it allows us to co-evolve both aspects of test case generation. We evaluate our approach by performing an empirical study on 20 Java classes from the three most popular JSON parsers across multiple search budgets. Our results show that the proposed approach on average improves branch coverage for JSON related classes by 15% (with a maximum increase of 50%) without negatively impacting other classes."

authors: ["Mitchell Olsthoorn", "Arie van Deursen", "Annibale Panichella"]
tags:
  [
    "Fuzzing",
    "Test Case Generation",
    "Search-Based Software Engineering",
    "Many-objective Optimization",
    "EvoSuite",
  ]
categories: []
date: 2020-07-06T14:29:50+02:00
lastmod: 2020-07-06T14:29:50+02:00
featured: true
draft: false
publication_types: ["1"]
publication: "The 35th IEEE/ACM International Conference on Automated Software Engineering (ASE) - New Ideas and Emerging Results (NIER) track"

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
projects: [ubri]

# Links (optional).
url_pdf: ""
url_preprint: "https://research.tudelft.nl/files/82771549/ASE_2020_Pure.pdf"
url_code: "https://doi.org/10.5281/zenodo.4001744"
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""
---

---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Guiding Automated Test Case Generation for Transaction-Reverting Statements in Smart Contracts"
subtitle: ""
summary: "Transaction-reverting statements are key constructs within Solidity that are extensively used for authority and validity checks. Current state-of-the-art search-based testing and fuzzing approaches do not explicitly handle these statements and therefore can not effectively detect security vulnerabilities. In this paper, we argue that it is critical to directly handle and test these statements to assess that they correctly protect the contracts against invalid requests. To this aim, we propose a new approach that improves the search guidance for these transaction-reverting statements based on interprocedural control dependency analysis, in addition to the traditional coverage criteria. We assess the benefits of our approach by performing an empirical study on 100 smart contracts w.r.t. transaction-reverting statement coverage and vulnerability detection capability. Our results show that the proposed approach can improve the performance of DynaMOSA, the state-of-the-art algorithm for test case generation. On average, we improve transaction-reverting statement coverage by 14 % (up to 35 %), line coverage by 8 % (up to 32 %), and vulnerability-detection capability by 17 % (up to 50 %)."
authors: ["Mitchell Olsthoorn", "Arie van Deursen", "Annibale Panichella"]
tags: ["Test Case Generation", "Fuzzing","Smart Contracts", "Search-based Software Engineering"]
categories: []
date: 2022-06-11T18:43:48+02:00
lastmod: 2022-06-11T18:43:48+02:00
featured: true
draft: false
publication_types: ["1"]
publication: "The 38th IEEE International Conference on Software Maintenance and Evolution (ICSME 2022)"

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
projects: ["Ripple"]

url_pdf: ""
url_preprint: "https://pure.tudelft.nl/ws/portalfiles/portal/124592082/main.pdf"
url_code: "https://github.com/syntest-framework/syntest-solidity"
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""
---

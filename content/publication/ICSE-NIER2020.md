---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "What Are We Really Testing in Mutation Testing for Machine Learning? A Critical Reflection"
subtitle: ""
summary: "Mutation testing is a well-established technique for assessing a test suite's effectiveness by injecting artificial faults into production code. In recent years, mutation testing has been extended to machine learning (ML) systems and deep learning (DL) in particular. Researchers have proposed approaches, tools, and statistically sound heuristics to determine whether mutants in DL systems are killed or not. However, as we will argue in this work, questions can be raised to what extent currently used mutation testing techniques in DL are actually in line with the classical interpretation of mutation testing. As we will discuss, in current approaches, the distinction between production and test code is blurry, the realism of mutation operators can be challenged, and generally, the degree to which the hypotheses underlying classical mutation testing (competent programmer hypothesis and coupling effect hypothesis) are followed lacks focus and explicit mappings.
In this paper, we observe that ML model development follows a test-driven development (TDD) process, where data points (test data) with labels (implicit assertions) correspond to test cases in traditional software. Based on this perspective, we critically revisit existing mutation operators for ML, the mutation testing paradigm for ML, and its fundamental hypotheses. Based on our observations, we propose several action points for better alignment of mutation testing techniques for ML with paradigms and vocabularies of classical mutation testing."

authors: ["Annibale Panichella", "Cynthia C. S. Liem"]
tags: ["Fuzzing", "Mutation Testing", "Machine Learning", "Software Testing", "Deep Learning"]
categories: []
date: 2021-01-18T14:29:50+02:00
lastmod: 2020-01-18T14:29:50+02:00
featured: true
draft: false
publication_types: ["1"]
publication: "The 43rd IEEE/ACM International Conference on Software Engineering 2021 - New Ideas and Emerging Results (ICSE-NIER)"

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
projects: []

# Links (optional).
url_pdf: ""
url_preprint: ""
url_code: ""
url_dataset: ""
url_project: ""
url_slides: ""
url_video: ""
url_poster: ""
url_source: ""

---

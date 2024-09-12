---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Systematic Comparison of Search-Based Approaches for LDA Hyperparameter Tuning"
subtitle: ""
summary: "Context: Latent Dirichlet Allocation (LDA) has been successfully used in the literature to extract topics from software documents and support developers in various software engineering tasks. While LDA has been mostly used with default settings, previous studies showed that default hyperparameter values generate sub-optimal topics from software documents. 
Objective: Recent studies applied meta-heuristic search (mostly evolutionary algorithms) to configure LDA in an unsupervised and automated fashion. However, previous work advocated for different meta-heuristics and surrogate metrics to optimize. The objective of this paper is to shed light on the influence of these two factors when tuning LDA for SE tasks. 
Method: 
We empirically evaluated and compared seven state-of-the-art meta-heuristics and three alternative surrogate metrics (i.e., fitness functions) to solve the problem of identifying duplicate bug reports with LDA. The benchmark consists of ten real-world and open-source projects from the Bench4BL dataset. 
Results:
Our results indicate that (1) meta-heuristics are mostly comparable to one another (except for random search and CMA-ES), and (2) the choice of the surrogate metric impacts the quality of the generated topics and the tuning overhead. Furthermore, calibrating LDA helps identify twice as many duplicates than untuned LDA when inspecting the top five past similar reports.
Conclusion:
No meta-heuristic and/or fitness function outperforms all the others, as advocated in prior studies. However, we can make recommendations for some combinations of meta-heuristics and fitness functions over others for practical use. Future work should focus on improving the surrogate metrics used to calibrate/tune LDA in an unsupervised fashion."
authors: ["Annibale Panichella"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types: ["2"]
publication: "Information and Software Technology"

tags: ["Topic Modeling", "Latent Dirichlet Allocation", "Search-based Software Engineering", " Meta-heuristics",
"Bug Reports", "Hyperparameter optimization"]
categories: []
date: 2020-09-09T21:50:29+02:00
lastmod: 2020-09-09T21:50:29+02:00
featured: false
draft: false

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

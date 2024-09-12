---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Breaking the Silence: the Threats of Using LLMs in Software Engineering"
subtitle: ""
summary: "Large Language Models (LLMs) have gained considerable traction within the Software Engineering (SE) community, impacting various SE tasks from code completion to test generation, from program repair to code summarization. Despite their promise, researchers must still be careful as numerous intricate factors can influence the outcomes of experiments involving LLMs. 
This paper initiates an open discussion on potential threats to the validity of LLM-based research including issues such as closed-source models, possible data leakage between LLM training data and research evaluation, and the reproducibility of LLM-based findings.
In response, this paper proposes a set of guidelines tailored for SE researchers and Language Model (LM) providers to mitigate these concerns.
The implications of the guidelines are illustrated using existing good practices followed by LLM providers and a practical example for SE researchers in the context of test case generation."

authors: ["June Sallou", "Thomas Durieux","Annibale Panichella"]
tags: ["Large Language Models", "Artificial Intelligence", "Replicability", "Empirical Software Engineering", "AI4SE"]
categories: []
date: 2024-01-01T14:29:50+02:00
lastmod: 2024-01-04T14:29:50+02:00
featured: true
draft: false
publication_types: ["1"]
publication: "The 46th IEEE/ACM International Conference on Software Engineering - New Ideas and Emerging Results (ICSE-NIER 2024)"

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

# Abstract

Large Language Models (LLMs) have gained considerable traction within the Software Engineering (SE) community, impacting various SE tasks from code completion to test generation, from program repair to code summarization. Despite their promise, researchers must still be careful as numerous intricate factors can influence the outcomes of experiments involving LLMs. 
This paper initiates an open discussion on potential threats to the validity of LLM-based research including issues such as closed-source models, possible data leakage between LLM training data and research evaluation, and the reproducibility of LLM-based findings.
In response, this paper proposes a set of guidelines tailored for SE researchers and Language Model (LM) providers to mitigate these concerns.
The implications of the guidelines are illustrated using existing good practices followed by LLM providers and a practical example for SE researchers in the context of test case generation.

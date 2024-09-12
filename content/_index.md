---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        CISELab
      image:
        filename: icon.png
      text: |
        <br>
        
        The Computational Intelligence for Software Engineering Lab (CISELab) is a center of excellence in Software Engineering and Computational Intelligence research, teaching, and practice.
  
  - block: collection
    content:
      title: About Us
      subtitle:
      text: "The development, maintenance, and testing of large software products involve many activities that are complex, expensive, and error-prone.
For example, complex systems (e.g., autonomous cars) are typically built as a composition of features that tend to interact and impact one another’s behavior in unknown ways.
Detecting feature interaction failures with manual testing becomes infeasible and too expensive when the number and the complexity of the features increase.
<br>
<br>
There are many tribes of AI, namely Symbolists, Evolutionists, Bayesians, Kernel Conservatives, Connectionists).
In the CISELab, we focus on applying **Computational Intelligence** (CI) to automate expensive development activities since more development automation would require fewer human resources.
One of the most common ways to make such automation is the **Search-Based Software Engineering** (SBSE), which reformulates traditional software engineering tasks as search (optimization) problems.
Then, **CI algorithms** (e.g., genetic algorithms, genetic programming, simulated annealing) are used to automate the process of discovering (e.g., detecting software defects) and building optimal solutions (e.g., software fixes).
SBSE is not only an academic research area, but it is achieving significant uptake in many industrial sectors.
<br><br>
We also employ CI algorithms to fine tune, evolve, and test **large language models** (LLMs) and **generative AI** when applied to Software Engineering tasks.
"
#<br><br>
#For example, **Facebook** uses multi-objective solvers to automatically design system-level test cases for mobile apps [[1]](https://link.springer.com/chapter/#10.1007/978-3-319-99241-9_1); Google uses multi-objective solvers for regression testing [[2]](http://sebase.cs.ucl.ac.uk/fileadmin/crest/sebasepaper/YooNH11_01.pdf).
#SSBSE techniques has been also applied in the automotive domain (**IEE S.A.** [[3]](https://pure.tudelft.nl/portal/files/45811366/paperASE18N2016pdf.pdf)), in satellite #domain (**SES S.A.** [[4]](https://pure.tudelft.nl/admin/files/47344874/main.pdf)) and security testing.
      count: 5
      filters:
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: about
    design:
      view: card
      columns: '2'
  
  - block: collection
    content:
      title: Topics
      subtitle:
      text: "
At the Computational Intelligence Lab, our research topics include but are not limited to the following research topics:
<br><br>
- **Blockchain Testing and Analysis** <br>
- **Testing for Machine Learning** <br>
- **Test Case Generation and Fuzzing** (i.e., unit, system, and integration level) <br>
- **Testing Cyber Physical Systems** (e.g., self-driving cars). <br>
- **Automated Program Repair** (including genetic programming) <br>
"
      count: 5
      filters:
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: about
    design:
      view: card
      columns: '2'

  - block: collection
    content:
      title: Organization
      subtitle:
      text: "
The CISELab is part of the [Software Engineering Research Group (SERG)](https://se.ewi.tudelft.nl/).
SERG is again part of the Faculty of Electrical Engineering, Mathematics, and Computer Science (EEMCS) within the [Delft University of Technology (TU Delft)](https://www.tudelft.nl/).
"
      count: 5
      filters:
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: about
    design:
      view: card
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: icon.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
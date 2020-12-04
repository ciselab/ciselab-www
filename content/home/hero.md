+++
# Hero widget.
widget = "pages"  # See https://wowchemy.com/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 20  # Order that this section will appear.

title = "About us"

# Hero image (optional). Enter filename of an image in the `static/media/` folder.
hero_media = "hero-academic.png"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  #gradient_start = "#4bb4e3"
  #gradient_end = "#2b94c3"
  
  # Background image.
  # image = ""  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
  # image_parallax = true  # Use a fun parallax-like fixed background effect? true/false
  
  # Text color (true=light or false=dark).
  text_color_light = false

# Call to action links (optional).
#   Display link(s) by specifying a URL and label below. Icon is optional for `[cta]`.
#   Remove a link/note by deleting a cta/note block.
#[cta]
 # url = "https://wowchemy.com/docs/install/"
 # label = "Get Started"
 # icon_pack = "fas"
 # icon = "download"
  
#[cta_alt]
# url = "https://wowchemy.com"
 #label = "View Documentation"

+++

The development, maintenance, and testing of large software products involve many activities that are complex, expensive, and error-prone. For example, complex systems (e.g., autonomous cars) are typically built as a composition of features that tend to interact and impact one another’s behavior in unknown ways. Detecting feature interaction failures with manual testing becomes infeasible and too expensive when the number and the complexity of the features increase.

There are many tribes of AI, namely Symbolists, Evolutionists, Bayesians, Kernel Conservatives, Connectionists). In the CISE Lab, we focus on applying **Computational Intelligence** (CI) to automate expensive development activities since more development automation would require fewer human resources.  One of the most common ways to make such automation is the **Search-Based Software Engineering** (SBSE), which reformulates traditional software engineering tasks as search (optimization) problems. Then, **CI algorithms** (e.g., genetic algorithms, genetic programming, simulated annealing) are used to automate the process of discovering (e.g., detecting software defects) and building optimal solutions (e.g., software fixes).

SBSE is not only an academic research area, but it is achieving significant uptake in many industrial sectors. For example, **Facebook** uses multi-objective solvers to automatically design system-level test cases for mobile apps [[1]](https://link.springer.com/chapter/10.1007/978-3-319-99241-9_1);  Google uses multi-objective solvers for regression testing [[2]](http://sebase.cs.ucl.ac.uk/fileadmin/crest/sebasepaper/YooNH11_01.pdf). SSBSE techniques has been also applied in the automotive domain (**IEE S.A.** [[3]](https://pure.tudelft.nl/portal/files/45811366/paperASE18N2016pdf.pdf)), in satellite domain (**SES S.A.** [[4]](https://pure.tudelft.nl/admin/files/47344874/main.pdf)) and security testing.

At the Computational Intelligence Lab,  our research topics include but are not limited to the following research topics:

* **Blockchain Testing and Analysis**

* **Testing for Machine Learning**

* **Test Case Generation and Fuzzing** (unit, system, and integration level)

* **Testing Cyber Physical Systems** (e.g., self-driving cars).

* **Automated Program Repair** (including genetic programming)


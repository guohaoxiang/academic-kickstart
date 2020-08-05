+++
title = "Cut-enhanced PolyCube-Maps for Feature-aware All-Hex Meshing"
date = 2020-08-03

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Hao-Xiang Guo", "Xiaohan Liu", "Dong-Ming Yan", "Yang Liu"]

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
publication = ""
publication_short = ""

# Abstract.
abstract = "Volumetric PolyCube-Map-based methods off er automatic ways to construct all-hexahedral meshes for closed 3D polyhedral domains, but their meshing quality is limited by the lack of interior singularities and feature alignment. In the presented work, we propose cut-enhanced PolyCube-Maps, to introduce essential interior singularities and preserve most input features. Our main idea is simple and intuitive: by inserting proper parameterization seams into the initial PolyCube-Map via novel PolyCube cutting operations, the mapping distortion can be reduced significantly.The cut-enhanced PolyCube-Map computation includes feature-aware PolyCube-Map construction and cut-enhanced PolyCube deformation. The former aims to preserve input feature edges during the initial PolyCube-Map construction. The latter introduces seams into the volumetric PolyCube shape by cutting it through selective PolyCube edges and deforms the modified PolyCube under the seamless constraints to compute a low-distortion PolyCube-Map. The hexahedral mesh induced by the fi nal PolyCube-Map can be further enhanced by our mesh improvement algorithm. We validate the efficacy of our method on a collection of more than one hundred CAD models and demonstrate its advantages over other automatic all-hex meshing methods and padding strategies. The limitations of cut-enhanced PolyCube-Maps are also discussed thoroughly."

# Summary. An optional shortened abstract.
summary = "SIGGRAPH 2020"

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Hex", "PolyCube", "cut", "feature"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = "https://app.box.com/s/e6nb0ert440zbul6i84gl28u060b027t"
url_preprint = ""
url_code = "https://github.com/msraig/CE-PolyCube"
url_dataset = "https://drive.google.com/file/d/1g1RwWSkPRhl4HpcstE5hJALF3Zpq61pQ/view"
url_project = "https://guohaoxiang.github.io/projects/ce_polycube.html"
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
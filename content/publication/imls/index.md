+++
title = "Deep Implicit Moving Least-Squares Functions for 3D Reconstruction"
date = 2021-03-21

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shi-Lin Liu", "Hao-Xiang Guo", "Hao Pan", "Pengshuai Wang", "Xin Tong", "Yang Liu"]


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
abstract = "Point  set  is  a  flexible  and  lightweight  representationwidely used for 3D deep learning. However, their discretenature prevents them from representing continuous and finegeometry, posing a major issue for learning-based shapegeneration.   In this work,  we turn the discrete point setsinto smooth surfaces by introducing the well-known implicitmoving least-squares (IMLS) surface formulation, which nat-urally defines locally implicit functions on point sets.  Weincorporate IMLS surface generation into deep neural net-works for inheriting both the flexibility of point sets andthe  high  quality  of  implicit  surfaces.   Our  IMLSNet  pre-dicts an octree structure as a scaffold for generating MLSpoints where needed and characterizes shape geometry withlearned local priors. Furthermore, our implicit function eval-uation is independent of the neural network once the MLSpoints are predicted, thus enabling fast runtime evaluation.Our experiments on 3D object reconstruction demonstratethat IMLSNets outperform state-of-the-art learning-basedmethods in terms of reconstruction quality and computa-tional efficiency. Extensive ablation tests also validate ournetwork design and loss functions."

# Summary. An optional shortened abstract.
summary = "CVPR 2021"

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Reconstruction", "Point cloud", "Implicit function"]

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
url_pdf = "https://arxiv.org/abs/2103.12266"
url_preprint = ""
url_code = "https://github.com/Andy97/DeepMLS"
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
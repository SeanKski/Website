---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Explaining Distribution Shifts"
authors: 
  - admin
  - David I. Inouye]
date: '2022-10-19T17:47:22-04:00'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-10T17:47:22-04:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*ArXiv*"
publication_short: "*ArXiv*"

abstract: "A distribution shift can have fundamental consequences such as signaling a change in the operating environment or significantly reducing the accuracy of downstream models. Thus, understanding distribution shifts is critical for examining and hopefully mitigating the effect of such a shift. Most prior work has focused on merely detecting if a shift has occurred and assumes any detected shift can be understood and handled appropriately by a human operator. We hope to aid in these manual mitigation tasks by explaining the distribution shift using interpretable transportation maps from the original distribution to the shifted one. We derive our interpretable mappings from a relaxation of the optimal transport problem, where the candidate mappings are restricted to a set of interpretable mappings. We then use quintessential examples of distribution shift in simulated and real-world cases to showcase how our explanatory mappings provide a better balance between detail and interpretability than the de facto standard mean shift explanation by both visual inspection and our PercentExplained metric."

# Summary. An optional shortened abstract.
summary: "We answer the question: ''What is a distribution shift explanation?'' and introduce a novel framework for explaining distribution shifts via transportation maps between a source and target distribution which are either inherently interpretable or interpreted using post-hoc interpretability methods."

tags: [Machine Learning, Distribution Shift, Explainable AI]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'towards-explaining-distribution-shifts'
url_code: 'https://github.com/inouye-lab/explaining-distribution-shifts'
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  placement: 2
  caption: ""
  focal_point: "Top"
  preview_only: false
  class: "featured-image"

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

---
Our paper can be found via clicking on the PDF icon at the top! Please reach out if you have any questions. Cheers :)

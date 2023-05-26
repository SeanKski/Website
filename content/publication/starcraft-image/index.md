---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "StarCraftImage: A Dataset For Prototyping Spatial Reasoning
Methods For Multi-Agent Environments"
authors: 
  - admin
  - Nicholas R. Waytowich
  - James Z. Hare
  - David I. Inouye
date: '2023-06-26T17:47:22-04:00'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-10T17:47:22-04:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition*"
publication_short: "*CVPR*"

abstract: "Spatial reasoning tasks in multi-agent environments such as event prediction, agent type identification, or missing data imputation are important for multiple applications (e.g., autonomous surveillance over sensor networks and subtasks for reinforcement learning (RL)). StarCraft II game replays encode intelligent (and adversarial) multi-agent behavior and could provide a testbed for these tasks; however, extracting simple and standardized representations for prototyping these tasks is laborious and hinders reproducibility. In contrast, MNIST and CIFAR10, despite their extreme simplicity, have enabled rapid prototyping and reproducibility of ML methods. Following the simplicity of these datasets, we construct a benchmark spatial reasoning dataset based on StarCraft II replays that exhibit complex multi-agent behaviors, while still being as easy to use as MNIST and CIFAR10. Specifically, we carefully summarize a window of 255 consecutive game states to create 3.6 million summary images from 60,000 replays, including all relevant metadata such as game outcome and player races. We develop three formats of decreasing complexity: Hyperspectral images that include one channel for every unit type (similar to multispectral geospatial images), RGB images that mimic CIFAR10, and grayscale images that mimic MNIST. We show how this dataset can be used for prototyping spatial reasoning methods. All datasets, code for extraction, and code for dataset loading can be found at https://starcraftdata.davidinouye.com/."

# Summary. An optional shortened abstract.
summary: "We introduce a large-scale easy to use spatial reasoning including 3.6 million images summarizing 10-seconds of human-played matches from the StarCraft II video game."

tags: [Machine Learning, Computer Vision, Datasets, StarCraft II]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'starcraft-image'
url_code: 'https://github.com/inouye-lab/starcraftimage'
url_dataset: 'https://starcraftdata.davidinouye.com/'
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

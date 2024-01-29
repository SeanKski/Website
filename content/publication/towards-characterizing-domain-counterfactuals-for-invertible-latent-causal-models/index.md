---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Characterizing Domain Counterfactuals For Invertible Latent Causal Models"
authors: ['Sean Kulinski*', 'Zeyu Zhou*', 'Ruqi Bai*', 'Murat Kocaoglu', 'David I. Inouye']
date: '2024-05-01T17:47:22-04:00'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-10T17:47:22-04:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Learning Representations"
publication_short: "*ICLR*"

abstract: "Answering counterfactual queries has many important applications such as knowledge discovery and explainability, but is challenging when causal variables are unobserved and we only see a projection onto an observation space, for instance, image pixels.
One approach is to recover the latent Structural Causal Model (SCM), but this typically needs unrealistic assumptions, such as linearity of the causal mechanisms.
Another approach is to use naive ML approximations, such as generative models, to generate counterfactual samples; however, these lack guarantees of accuracy.
In this work, we strive to strike a balance between practicality and theoretical guarantees by focusing on a specific type of causal query called *domain counterfactuals*, which hypothesizes what a sample would have looked like if it had been generated in a different domain (or environment).
Concretely, by only assuming invertibility and access to observational data from different domains, we aim to improve domain counterfactual estimation both theoretically and practically.
We define *domain counterfactually equivalent* models and prove necessary and sufficient properties for equivalent models that provide a tight characterization of the domain counterfactual equivalence classes.
Building upon this result, we prove that every equivalence class contains a model where all intervened variables are at the end when topologically sorted by the causal DAG, i.e., all non-intervened variables have no intervened ancestors.
This surprising result suggests that a model design that only allows intervention in the last $k$ latent variables may improve model estimation for counterfactuals.
We then test this model design on extensive simulated and image-based experiments which show the sparse canonical model indeed improves counterfactual estimation over baseline non-sparse models."

# Summary. An optional shortened abstract.
summary: "We build generative models by learning latent causal models from data observed from different domains for the purpose of
generating domain counterfactuals, and further characterize the equivalence classes for such latent causal models."

tags: [Machine Learning, Causal Learning, Generative Modeling, Domain Generalization]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 'towards-characterizing-domain-counterfactuals-for-invertible-latent-causal-models'
url_code:
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

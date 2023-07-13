---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Characterizing Domain Counterfactuals For Invertible Latent Causal Models"
authors: 
  - admin
  - Zeyu Zhou
  - Ruqi Bai
  - Murat Kocaoglu
  - David I. Inouye
date: '2023-07-01T17:47:22-04:00'
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-10T17:47:22-04:00'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "*arXiv"
publication_short: "*arXiv*"

abstract: "Learning latent causal models from data has many important applications such as robustness, model extrapolation, and counterfactuals. Most prior theoretic work has focused on full causal discovery (i.e., recovering the true latent variables) but requires strong assumptions such as linearity or fails to have any analysis of the equivalence class of solutions (e.g., IRM). Instead of full causal discovery, we focus on a specific type of causal query called the domain counterfactual, which hypothesizes what a sample would have looked like if it had been generated in a different domain (or environment). Concretely, we assume domain-specific invertible latent structural causal models and a shared invertible observation function, both of which are less restrictive assumptions than prior theoretic works. Under these assumptions, we define domain counterfactually equivalent models and prove that any model can be transformed into an equivalent model via two invertible functions. This constructive property provides a tight characterization of the domain counterfactual equivalence classes. Building upon this result, we prove that every equivalence class contains a model where all intervened variables are at the end when topologically sorted by the causal DAG, i.e., all non-intervened variables have non-intervened ancestors. This surprising result suggests that an algorithm that only allows intervention in the last k latent variables may improve model estimation for counterfactuals. In experiments, we enforce the sparse intervention hypothesis via this theoretic result by constraining that the latent SCMs can only differ in the last few causal mechanisms and demonstrate the feasibility of this algorithm in simulated and image-based experiments."

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

---
# Experience widget.
widget: experience  # See https://sourcethemes.com/academic/docs/page-builder/
headless: true  # This file represents a page section.
active: true  # Activate this widget? true/false
weight: 40  # Order that this section will appear.

title: Experience
subtitle: 

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

design:
  columns: '1'
  
experience:
  - title: Ph.D. Research (Machine Learning; Natural Language Processing; Computer Vision)
    company: Purdue University, under advisory of Dr. David Inouye
    company_url: 'https://www.davidinouye.com'
    company_logo: purdue
    location: West Lafayette, Indiana
    date_start: '2019-08-17'
    date_end: ''
    description: |2-
      - • Creating a causally-grounded generative AI model that generates counterfactual examples that answer the question "What would this look like if X had happened instead of Y" (e.g., what would my chest x-ray look like if I had gone to Hospital B instead of Hospital A) [[Preprint Publication](https://arxiv.org/abs/2306.11281)]
      - Derived methods for interpretable optimal transport for the purposes of explaining distribution shifts to a human operator which can be used for system monitoring or knowledge discovery. [[ICML Publication](https://arxiv.org/abs/2210.10275)] [[code](https://github.com/inouye-lab/explaining-distribution-shifts)].
      - Constructed a new large-scale CV dataset based on human matches of StarCraft II that exhibits complex and shifting multi-agent behaviors yielding 1.8 million images with multiple data representations such as ones that can be used as a drop-in replacement for CIFAR10 and MNIST. [[CVPR Publication](https://openaccess.thecvf.com/content/CVPR2023/papers/Kulinski_StarCraftImage_A_Dataset_for_Prototyping_Spatial_Reasoning_Methods_for_Multi-Agent_CVPR_2023_paper.pdf)] [[code](https://starcraftdata.davidinouye.com/)]
      - Created a lightweight machine learning algorithm that uses deep density models to detect shifts in distributions as well as determine which feature(s) are causing the shift, allowing for online monitoring with little additional overhead. [[NeurIPS publication](https://proceedings.neurips.cc/paper/2020/file/e2d52448d36918c575fa79d88647ba66-Paper.pdf)] [[code](https://github.com/inouye-lab/feature-shift)].

  - title: Researcher Intern (Deep Learning; ML Ops), 
    company: Microsoft Research
    company_url: 'https://www.microsoft.com/en-us/research/research-area/artificial-intelligence/?'
    company_logo: microsoft
    location: Seattle, WA
    date_start: '2023-05-31'
    date_end: '2023-08-31'
    description: |2-
      - Created a forecasting model that can predict the future performance of large machine learning models (e.g., foundation models) that are deployed on high dimensional streaming data - i.e. predicting model failure before it happens.
      - Developed a compute-efficient retraining/finetuning algorithm that can mitigate ML performance degradation on complex realistic distribution shifts such as combinations of covariate drift and concept drift.
      - This work has been patented and is being integrated into the Azure Machine Learning monitoring toolbox.

  - title: Data Scientist Intern (Natural Language Processing; Search)
    company: Microsoft
    company_url: 'https://www.microsoft.com/en-us/research/group/msai/'
    company_logo: microsoft
    location: Seattle, WA
    date_start: '2022-05-31'
    date_end: '2022-08-31'
    description: |2-
        This work with Microsoft365 Research studied using generative language models (e.g., LLMs) to improve enterprise search results in Microsoft Apps by adding related search terms to the user's search query.  
        - We used Natural Language Processing (NLP) models (e.g., GPTx) to generate related search terms for a given query and designed an additional NLP model to evaluate the relevance of the generative additions -- which has been integrated into the Microsoft Office Query Understanding pipeline and greatly improved the query alternations.
        - Identified and explored bridging the gap between web search methods (e.g., Google search or Bing search) and enterprise search methods (e.g., Outlook search or Teams search).

  - title: ML Scientist (Computer Vision)
    company: AbbVie
    company_url: https://www.abbvie.com/our-science.html
    company_logo: abbvie
    location: San Fransisco, CA
    date_start: '2021-10-01'
    date_end: '2022-05-31'
    description: |2-
        - Led the design and development of a novel computer vision model for processing large-scale histopathological images for the purpose of cancer detection and downstream diagnosis.
        - Developed robust high-performance pipeline for continuous analysis of whole slide images for deployment to consumers.
        - Assisted in building a consumer-facing ML deployment platform with a custom viewer+annotator web-app for displaying mappings and meta-statistics generated by the model.

  - title: Research Intern (Computer Vision, Natural Language Processing)
    company: Lawrence Livermore National Laboratory
    company_url: https://computing.llnl.gov/casc/machine-intelligence-group
    company_logo: llnl
    location: Livermore, California
    date_start: '2020-05-28'
    date_end: '2020-08-18'
    description: |2-
        - Identified issues in state-of-the-art computer vision frameworks for detection of COVID-19 which were leading to misclassification.
        - Built computer vision models to conquer some of these issues, such as being robust to spatial distribution shifts. The models were trained using Livermore's Sierra HPC system.
        - Used Natural Language Processing techniques on parsed Material Science publications to create an interpretable deep model to aid in the discovery of new nanostructures and nanomaterials.

  - title: Software Engineer  (Machine Learning)
    company: Indiana Microelectronics
    company_url: https://www.indianamicro.com/
    company_logo: indianamicro
    location: West Lafayette, Indiana
    date_start: '2019-01-07'
    date_end: '2019-08-18'
    description: |2-
        - Developed Genetic Algorithm to automate and optimize design of transmission zero filter for Lockheed Martin.
        - Designed automated testing of temperature drift for a closed-loop linear piezoelectric motor.
        - Oversaw testing, calibration, and reworks for a phased-array filter system.
---
---
# Experience widget.
widget: experience  # See https://sourcethemes.com/academic/docs/page-builder/
headless: true  # This file represents a page section.
active: true  # Activate this widget? true/false
weight: 30  # Order that this section will appear.

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
  - title: ML Research Assistant
    company: Purdue University, under advisory of Dr. David Inouye
    company_url: 'https://www.davidinouye.com'
    company_logo: purdue
    location: West Lafayette, Indiana
    date_start: '2019-08-17'
    date_end: ''
    description: |2-
      - Creating approach for casual discovery via aligning the latent distributions of data gathered from heterogeneous domains (e.g., tissue samples from different hospitals).
      - Derived method for interpretable optimal transport for the purposes of explaining image-based distribution shifts to a human operator which can be used for system monitoring or knowledge discovery [[publication](https://www.seankulinski.com/publication/towards-explaining-image-based-shifts/)].
      - Constructed an interpretable benchmark Sensor Network dataset based on StarCraft II replays yielding 1.8 million game-state windows with multiple data representations such as ones that can be used as a drop-in replacement for CIFAR10 and MNIST.
      - Created a light-weight machine learning algorithm which uses deep density models to detect shifts in distributions as well as determine which feature(s) are causing the shift, allowing for online monitoring with little additional overhead [[publication](https://www.seankulinski.com/publication/feature-shift-detection/)] [[code](https://github.com/inouye-lab/feature-shift)].

  - title: Data Scientist, Intern
    company: Microsoft
    company_url: 'https://www.microsoft.com/en-us/research/group/msai/'
    company_logo: microsoft
    location: Seattle, WA
    date_start: '2022-05-31'
    date_end: '2022-08-31'
    description: |2-
        Worked in M365 Research to develop Natural Language Processing (NLP) models to allow for better search relevance across Microsoft365 applications.  
        - Designed an NLP model that detects if multiple enterprise search queries have the same intent, for the main purpose of measuring the semantic change of a query alteration.  
        - Identified and explored knowledge gap between web search methods (e.g., Google search or Bing search) and enterprise search methods (e.g., Outlook search or Teams search).  
        - Created training pipeline which adapts open web search data to better fit enterprise search training data.  

  - title: ML Scientist
    company: AbbVie
    company_url: https://www.abbvie.com/our-science.html
    company_logo: abbvie
    location: San Fransisco, CA
    date_start: '2021-10-01'
    date_end: '2022-05-31'
    description: |2-
        - Lead the design and development of a novel computer vision model for processing histopathological images for the purpose of cancer detection and downstream diagnosis.  
        - Worked with a team to generate additional cancer related statistics to aid doctors in determining treatment modality.  
        - Developed robust high performance pipeline for continuous analysis of whole slide images for deployment to consumers.

  - title: ML Research, Intern
    company: Lawrence Livermore National Laboratory
    company_url: https://computing.llnl.gov/casc/machine-intelligence-group
    company_logo: llnl
    location: Livermore, California
    date_start: '2020-05-28'
    date_end: '2020-08-18'
    description: |2-
        - Identified issues in state-of-the-art computer vision frameworks for detection of COVID-19
        - Built computer vision models to conquer some of these issues, such as being robust to spatialdistribution shifts. The models were trained using Livermore???s Sierra HPC system.
        - Used Natural Language Processing techniques on parsed Material Science publications to createan interpretable deep model to aid in the synthesis of new nanostructures and nanomaterials.

  - title: Software Engineer
    company: Indiana Microelectronics
    company_url: https://www.indianamicro.com/
    company_logo: indianamicro
    location: West Lafayette, Indiana
    date_start: '2019-01-07'
    date_end: '2019-08-18'
    description: |2-
        - Developed Genetic Algorithm to automate and optimize design of transmission zero filter for Lockheed Martin
        - Designed automated testing of temperature drift for a closed-loop linear piezoelectric motor
        - Oversaw testing, calibration, and reworks for a phased-array filter system
---
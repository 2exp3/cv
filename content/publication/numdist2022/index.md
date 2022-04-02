---
title: "Running Online Behavioral Experiments Using R: Implementation of a Response-Time Decision Making Task as an R-Shiny App"
authors:
- admin
- Guillermo Solovey
date: "2022-01-07"
doi: "http://doi.org/10.5334/joc.200"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Cognition"
publication_short: ""

abstract: "Online experiments allow for fast, massive, cost-efficient data collection. However, uncontrolled conditions in online experiments can be problematic, particularly when inferences hinge on response-times (RTs) in the millisecond range. To address this challenge, we developed a mobile-friendly open-source application using R-Shiny, a popular R package. In particular, we aimed to replicate the numerical distance effect, a well-established cognitive phenomenon. In the task, 169 participants (109 with a mobile device, 60 on a desktop computer) completed 116 trials displaying two-digit target numbers and decided whether they were larger or smaller than a fixed standard number. Sessions lasted ~7-minutes. Using generalized linear mixed models estimated with Bayesian inference methods, we observed a numerical distance effect: RTs decreased with the logarithm of the absolute difference between the target and the standard. Our results support the use of R-Shiny for RT-data collection. Furthermore, our method allowed us to measure systematic shifts in recorded RTs related to different OSs, web browsers, and devices, with mobile devices inducing longer shifts than desktop devices. Our work shows that precise RT measures can be reliably obtained online across mobile and desktop devices. It further paves the ground for the design of simple experimental tasks using R, a widely popular programming framework among cognitive scientists."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes

featured: false

links:
- name: OSF (data and code)
  url: https://osf.io/6gmzs/
url_pdf: 'https://www.journalofcognition.org/articles/10.5334/joc.200/galley/581/download/'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.journalofcognition.org/articles/10.5334/joc.200/'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

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

---
title: "Time to shine: reliable timing using R-Shiny for online experiments (preprint)"
authors:
- admin
- Guillermo Solovey
date: "2020-11-01"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Online experiments are becoming an increasingly relevant tool for cognitive science research. Its appeal lies on the ability to reach a large number of participants in a short time at a relatively low cost. However, compared to controlled laboratory studies, online data is far more noisy. This is especially relevant when reliable timing at a millisecond-level is paramount, as it is the case for many decision making tasks. In this paper we sought to replicate a well-validated cognitive effect -the distance effect in number comparisons- using an online mobile-friendly app developed with open-source tools in R-Shiny. In this task, adapted from Dehaene et al, participants have to decide whether a number on the screen is larger or smaller than a standard (65 in our study). The distance effect stands for the fact that response time (RT) is significantly larger as the presented number is closer to 65. A total of  N=170 participants (110 with a mobile, 60 on a desktop computer) completed 116 trials over a ~7 min session. Using generalized linear mixed models (GLMMs) estimated with Bayesian inference methods, we found a numerical distance effect strikingly similar to the reported results in the original study. Furthermore, we found systematic offsets in RTs for different OS, browsers and devices. Our results demonstrate the reliability of timing-data collection with R-Shiny. By doing so, our work paves the ground for seamless and robust implementation of simple cognitive tasks in online studies over desktop and mobile devices using only R, a widely used programming framework among cognitive scientists.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes

featured: false

#links:
#- name: Custom Link
#  url: http://example.org
url_pdf: ''
url_code: 'https://osf.io/6gmzs/'
url_dataset: 'https://osf.io/6gmzs/'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://osf.io/6gmzs/'
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

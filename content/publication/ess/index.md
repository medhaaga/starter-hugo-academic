---
title: "A principled stopping rule for importance sampling"
authors:
- admin
- Dootika Vats
- Victor Elvira

date: "2021-08-30T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
#publication: "*Journal of Source Themes, 1*(1)"
#publication_short: ""

abstract: Importance sampling (IS) is a Monte Carlo technique that relies on weighted samples, simulated from a proposal distribution, to estimate intractable integrals. The quality of the estimators improves with the number of samples. However, for achieving a desired quality of estimation, the required number of samples is unknown, and depends on the quantity of interest, the estimator, and the chosen proposal. We present a sequential stopping rule that terminates simulation when the overall variability in estimation is relatively small. The proposed methodology closely connects to the idea of an effective sample size in IS and overcomes crucial shortcomings of existing metrics, e.g., it acknowledges multivariate estimation problems. Our stopping rule retains asymptotic guarantees and provides users a clear guideline on when to stop the simulation in IS.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin #tincidunt magna sed ex sollicitudin condimentum.



# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/abs/2108.13289
url_code: 'https://github.com/medhaaga/Importance-Sampling-Stopping-Rule'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

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
# slides: example
---


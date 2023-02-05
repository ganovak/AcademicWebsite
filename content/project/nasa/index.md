---
title: Defining Best Practices for Reproducible Research
summary: Recommendations for practices and tools (including a novel R package) for increasing reproducibility at Johnson Space Center's Biomedical Research and Environmental Sciences Division labs 
tags:
 - Research
date: "2020-08-06T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  #caption: Count Map
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: 
#url_code: ""
url_pdf: "files/abstract_nasa.pdf"
url_slides: "files/exit_presentation_sc_nasa.html"
#url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

# Defining Best Practices for Reproducibility

I synthesized the standards and guidance from a thorough literature review on the subject into a two-part report. The first contains software environment agnostic recommendations for strategies to increase reproducibility. The second extends this guidance by providing specific implementations for R and RStudio users leveraging R's standard library, a suite of extension packages and integrated softwares, and novel code. 

# Supporting Reproducibility

I developed `SKReproTools`, a R package for internal NASA use designed to combine existing R packages with novel code to produce a user-friendly reproducible workflow while abstracting away technical minutiae. The package is fully documented and includes a tutorial vignette highlighting its capabilities through a minimal reproducible project. Particularly exciting functionality includes extracting in-source documentation, package management and version control integration, execution order handling, and bundling capabilities for transportation or storage.
